# Bot Wars Bot Programming Documentation

Welcome to the comprehensive guide on coding bots for Bot Wars. This document explains the game environment, bot senses, available actions, helper libraries, and provides example strategies to help you build competitive bots.

---

## Table of Contents
- [Overview](#overview)
- [Game Environment & Bot Senses](#game-environment--bot-senses)
- [Bot Actions](#bot-actions)
- [Helper Libraries: Vectors](#helper-libraries-vectors)
  - [Detailed Vectors Library Documentation](#detailed-vectors-library-documentation)
- [Example Bot Scripts](#example-bot-scripts)

---

## Overview

**Bot Wars** is a competitive game where you program your bot using JavaScript. Your bot battles against other bots on a shrinking arena (ring). The objective is to survive by both avoiding the arena edge and knocking enemy bots out—often by pushing them beyond the ring’s boundary.

Every turn, your bot receives sensory information about its environment and then chooses an action (such as moving or honking) that will be executed on the next turn.

---

## Game Environment & Bot Senses

When your bot's code runs, you have access to several key data points (**bot senses**):

- **`myPos`**  
  Your current X, Y position.  
  *Format:* `{ x: number, y: number }`

- **`myVelocity`**  
  Your current moving velocity as a vector.  
  *Format:* `{ x: number, y: number }`

- **`ringCenterVector`**  
  A vector pointing from your bot to the center of the arena.  
  *Format:* `{ x: number, y: number }`

- **`ringCenterDistance`**  
  The distance (magnitude) from your bot to the arena center.  
  *Type:* `number`

- **`ringRadius`**  
  The current radius of the arena (which shrinks over time).  
  *Type:* `number`

- **`enemies`**  
  An array of enemy bot objects. Each enemy object includes:
  - **`id`**: Unique identifier.
  - **`label`**: Name of the enemy.
  - **`vector`**: A vector from your bot to the enemy.  
    *Format:* `{ x: number, y: number }`
  - **`distance`**: The magnitude of the enemy vector.
  - **`velocity`**: The enemy's current velocity vector.

---

## Bot Actions

Your bot has a limited set of actions. The primary actions are:

- **`act.move({ vector, force })`**  
  Moves your bot in the given direction with the specified force.
  - **`vector`**: An object with `x` and `y` properties (values between -1 and 1).
  - **`force`**: A number between 0 and 1 that determines the strength of the move.

  *Example:*
  ```javascript
  act.move({ vector: { x: 0.5, y: -0.5 }, force: 0.75 });

- **`act.honk()`**  
  Causes your bot to emit a honking sound. This action may serve as a distraction for opponents or trigger other in-game effects.

  *Example:*
  ```javascript
  act.honk();


# Helper Libraries: Vectors

The **vectors** library provides a suite of utility functions to simplify vector arithmetic. These functions help you manipulate 2D vectors for tasks such as rotating, normalizing, scaling, and blending vectors—core operations for creating movement and tactical behaviors in your bot.

## Detailed Vectors Library Documentation

### Overview

The **vectors** library is designed to handle common 2D vector operations. This section details the most commonly used functions:

### Available Functions

#### `vectors.rotateByDeg(vector, degrees)`
- **Description:** Rotates the given vector by the specified number of degrees.
- **Parameters:**
  - `vector`: The original vector.
  - `degrees`: Number of degrees to rotate.
- **Returns:** A new vector rotated by the given angle.

#### `vectors.normalize(vector)`
- **Description:** Returns the unit vector (a vector with magnitude 1) in the same direction as the given vector.
- **Parameters:**
  - `vector`: The vector to normalize.

#### `vectors.mix(vectorA, vectorB, factor)`
- **Description:** Blends two vectors together.
- **Parameters:**
  - `vectorA`: The base vector.
  - `vectorB`: The vector to blend with.
  - `factor`: A value between 0 and 1 determining the weight of `vectorB` in the mix.
- **Returns:** A new vector that is a mix of `vectorA` and `vectorB`.

#### `vectors.add(vectorA, vectorB)`
- **Description:** Returns the sum of two vectors.
- **Parameters:**
  - `vectorA` and `vectorB`: The vectors to add.

#### `vectors.multiplyScalar(vector, scalar)`
- **Description:** Multiplies each component of the vector by the given scalar.
- **Parameters:**
  - `vector`: The vector to scale.
  - `scalar`: The number by which to multiply the vector.

#### `vectors.dot(vectorA, vectorB)`
- **Description:** Computes the dot product of `vectorA` and `vectorB`.
- **Returns:** A scalar representing the dot product.

#### `vectors.invert(vector)`
- **Description:** Returns the inverted vector (each component multiplied by -1).
- **Parameters:**
  - `vector`: The vector to invert.

#### `vectors.magnitude(vector)` (or `vectors.vectorLength(vector)`)
- **Description:** Returns the magnitude (length) of the vector.

#### `vectors.limit(vector, max)`
- **Description:** Limits the magnitude of the vector to the specified maximum value.
- **Parameters:**
  - `vector`: The vector to limit.
  - `max`: The maximum allowed magnitude.

#### `vectors.subtract(vectorA, vectorB)`
- **Description:** Returns the difference between two vectors by subtracting `vectorB` from `vectorA`.

### Additional Helper Functions

The **vectors** library may also include functions for further vector operations:

#### Rotation Functions
- **`vectors.rotate(vector, radians)`**: Rotates the vector by the specified radians.
- **`vectors.rotateTo(vector, target)`**: Rotates one vector to align with another.

#### Other Utilities
- **`vectors.cross(vectorA, vectorB)`**: Computes the cross product (in 2D, often returns a scalar).
- **`vectors.distance(vectorA, vectorB)`**: Calculates the distance between two vectors.
- **`vectors.project(vectorA, vectorB)`**: Projects `vectorA` onto `vectorB`.
- **`vectors.copy(vector)`**: Returns a copy of the given vector.
- **`vectors.isZero(vector)`**: Checks if the vector is a zero vector.
- **`vectors.isEqual(vectorA, vectorB)`**: Checks if two vectors are equal.

These functions are critical for implementing complex movement strategies in your bot, ensuring you can accurately compute directions, distances, and safe navigation paths during gameplay.

# Example Bot Scripts:  
```
// Simple Bot: Always move directly toward the enemy with full force.
let enemy = enemies[0];
act.move({
    vector: enemy.vector,
    force: 1
});
```

```
// Simple Bot: Move toward the center at half force unless an enemy is within 150 units,
// then move toward the enemy with full force.
let enemy = enemies[0];

if (enemy.distance < 150) {
    act.move({
        vector: enemy.vector,
        force: 1
    });
} else {
    act.move({
        vector: ringCenterVector,
        force: 0.5
    });
}
```

```
// Bot: Move toward the enemy with full force when enemy is within 150 units,
// otherwise move 30° off of enemy.vector with half force.
let enemy = enemies[0];

if (enemy.distance < 150) {
    act.move({
        vector: enemy.vector,
        force: 1
    });
} else {
    act.move({
        vector: vectors.rotateByDeg(enemy.vector, 30),
        force: 0.5
    });
}

```
