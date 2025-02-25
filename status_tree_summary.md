# status_tree.txt – Full Path Summary

Below is a comprehensive list of **all** paths found in the file snippet (up to where the file was truncated).  
**Note**: Per your instructions, **only the first index of arrays** is included. Any subsequent indexes (1, 2, etc.) are omitted.  
Each bullet includes a short description.

---

## /status/system

- **/status/system**  
  Top-level system status.

- **/status/system/bootid**  
  Unique identifier for the current boot session.

- **/status/system/smanager**  
  System manager (startup process) data.

  - **/status/system/smanager/startup**  
    Tracks startup progress.

    - **/status/system/smanager/startup/starting**  
      Indicates the system startup is beginning.

    - **/status/system/smanager/startup/started**  
      Indicates the system startup is completed.

    - **/status/system/smanager/startup/svcs_started**  
      Indicates system services have been started.

- **/status/system/services**  
  Collection of individual system services.

  - **/status/system/services/mountfilesystem**  
    Mount filesystem service.
    - **/status/system/services/mountfilesystem/state**  
      Current state of this service.

  - **/status/system/services/passwd**  
    Password service.
    - **/status/system/services/passwd/state**  
      Current state of this service.

  - **/status/system/services/ledmgr**  
    LED management service.
    - **/status/system/services/ledmgr/state**  
      Current state.

  - **/status/system/services/watchdog**  
    Watchdog service to monitor system health.
    - **/status/system/services/watchdog/state**  
      Service state.

  - **/status/system/services/localnet**  
    Local network configuration service.
    - **/status/system/services/localnet/state**  
      Current state.

  - **/status/system/services/populatestatus**  
    Populates overall status data.
    - **/status/system/services/populatestatus/state**  
      Service state.

  - **/status/system/services/buttonledevent**  
    Button/LED event handling service.
    - **/status/system/services/buttonledevent/state**  
      Service state.

  - **/status/system/services/wm2**  
    Wireless management service (example).
    - **/status/system/services/wm2/state**  
      Current state.

  - **/status/system/services/gpio**  
    GPIO (General-Purpose I/O) service.
    - **/status/system/services/gpio/state**  
      Service state.

  - **/status/system/services/csreceiver**  
    Possibly a configuration/state receiver service.
    - **/status/system/services/csreceiver/state**  
      Service state.

  - **/status/system/services/rm**  
    Resource manager or related.
    - **/status/system/services/rm/state**  
      State of this service.

  - **/status/system/services/lan**  
    LAN interface manager.
    - **/status/system/services/lan/state**  
      Service state.

  - **/status/system/services/macfilt**  
    MAC filtering service.
    - **/status/system/services/macfilt/state**  
      Service state.

  - **/status/system/services/macmon**  
    MAC monitoring service.
    - **/status/system/services/macmon/state**  
      Current state.

  - **/status/system/services/obupgrade**  
    Over-the-bridge or out-of-band upgrade service.
    - **/status/system/services/obupgrade/state**  
      State info.

  - **/status/system/services/qualcommproxy**  
    A proxy service for Qualcomm chipset.
    - **/status/system/services/qualcommproxy/state**  
      Service state.

  - **/status/system/services/cpmodem_start**  
    Modem startup routines.
    - **/status/system/services/cpmodem_start/state**  
      Service state.

  - **/status/system/services/dnsmonitor**  
    DNS monitoring service.
    - **/status/system/services/dnsmonitor/state**  
      Service state.

  - **/status/system/services/clock**  
    Time/clock service.
    - **/status/system/services/clock/state**  
      Service state.

  - **/status/system/services/portmgr**  
    Port manager.
    - **/status/system/services/portmgr/state**  
      State.

  - **/status/system/services/id**  
    Identification service.
    - **/status/system/services/id/state**  
      Current state.

  - **/status/system/services/xlat464**  
    Translation mechanism (NAT64/464XLAT).
    - **/status/system/services/xlat464/state**  
      State.

  - **/status/system/services/certmgmt**  
    Certificate management service.
    - **/status/system/services/certmgmt/state**  
      State of cert mgmt.

  - **/status/system/services/gre**  
    GRE tunneling service.
    - **/status/system/services/gre/state**  
      State.

  - **/status/system/services/vti**  
    Virtual tunnel interface service.
    - **/status/system/services/vti/state**  
      State.

  - **/status/system/services/openvpn**  
    OpenVPN client or server service.
    - **/status/system/services/openvpn/state**  
      Service state.

  - **/status/system/services/wired_8021x**  
    802.1X for wired interfaces.
    - **/status/system/services/wired_8021x/state**  
      State.

  - **/status/system/services/nemo**  
    Possibly a networking mobility service.
    - **/status/system/services/nemo/state**  
      Current state.

  - **/status/system/services/hotspot**  
    Hotspot/captive portal service.
    - **/status/system/services/hotspot/state**  
      State.

  - **/status/system/services/qos**  
    Quality of Service manager.
    - **/status/system/services/qos/state**  
      Service state.

  - **/status/system/services/datacap**  
    Data usage cap service.
    - **/status/system/services/datacap/state**  
      State.

  - **/status/system/services/firewall**  
    Firewall service.
    - **/status/system/services/firewall/state**  
      State.

  - **/status/system/services/ulog**  
    System logging service (user-level?).
    - **/status/system/services/ulog/state**  
      State.

  - **/status/system/services/adminfilter**  
    Administrative filter service.
    - **/status/system/services/adminfilter/state**  
      Current state.

  - **/status/system/services/nat**  
    Network Address Translation service.
    - **/status/system/services/nat/state**  
      NAT state.

  - **/status/system/services/alg**  
    Application-level gateway service.
    - **/status/system/services/alg/state**  
      Service state.

  - **/status/system/services/sysinfo**  
    System info service.
    - **/status/system/services/sysinfo/state**  
      State.

  - **/status/system/services/logsystem**  
    System logging or log manager.
    - **/status/system/services/logsystem/state**  
      State.

  - **/status/system/services/vlan**  
    VLAN manager service.
    - **/status/system/services/vlan/state**  
      Service state.

  - **/status/system/services/cpmodem_done**  
    Modem finalization service.
    - **/status/system/services/cpmodem_done/state**  
      Current state.

  - **/status/system/services/pam**  
    Policy or plugin authentication manager.
    - **/status/system/services/pam/state**  
      State.

  - **/status/system/services/alert**  
    Alert manager service.
    - **/status/system/services/alert/state**  
      State.

  - **/status/system/services/sshserver**  
    SSH server service.
    - **/status/system/services/sshserver/state**  
      Service state.

  - **/status/system/services/cpmodem_remote_dispatch**  
    Remote dispatch for modem.
    - **/status/system/services/cpmodem_remote_dispatch/state**  
      State.

  - **/status/system/services/bluetooth**  
    Bluetooth subsystem service.
    - **/status/system/services/bluetooth/state**  
      State.

  - **/status/system/services/webfilter**  
    Web filtering service.
    - **/status/system/services/webfilter/state**  
      State.

  - **/status/system/services/containers**  
    Containerization service.
    - **/status/system/services/containers/state**  
      State.

  - **/status/system/services/mqtt**  
    MQTT messaging service.
    - **/status/system/services/mqtt/state**  
      Service state.

  - **/status/system/services/msft_iot**  
    Microsoft IoT integration service.
    - **/status/system/services/msft_iot/state**  
      State.

  - **/status/system/services/netperf**  
    Network performance measurement service.
    - **/status/system/services/netperf/state**  
      Service state.

  - **/status/system/services/power_usage**  
    Power usage tracking.
    - **/status/system/services/power_usage/state**  
      State.

  - **/status/system/services/scepclient**  
    SCEP (certificate enrollment) client service.
    - **/status/system/services/scepclient/state**  
      State.

  - **/status/system/services/schedreboot**  
    Scheduled reboot service.
    - **/status/system/services/schedreboot/state**  
      State.

  - **/status/system/services/shell**  
    Shell service (possibly console).
    - **/status/system/services/shell/state**  
      State.

  - **/status/system/services/shellExec**  
    Shell command execution service.
    - **/status/system/services/shellExec/state**  
      State.

  - **/status/system/services/storage_health**  
    Checks or monitors storage health.
    - **/status/system/services/storage_health/state**  
      State.

  - **/status/system/services/stp**  
    Spanning Tree Protocol service.
    - **/status/system/services/stp/state**  
      State.

  - **/status/system/services/tcpdump**  
    Packet capture (tcpdump) service.
    - **/status/system/services/tcpdump/state**  
      State.

  - **/status/system/services/wireless**  
    Wireless subsystem service.
    - **/status/system/services/wireless/state**  
      State.

  - **/status/system/services/wwan2**  
    Secondary WWAN service.
    - **/status/system/services/wwan2/state**  
      State.

  - **/status/system/services/zebra**  
    Routing daemon (Zebra) service.
    - **/status/system/services/zebra/state**  
      State.

  - **/status/system/services/poe-pse**  
    Power-over-Ethernet service.
    - **/status/system/services/poe-pse/state**  
      State.

  - **/status/system/services/traffic_class**  
    Traffic classification service.
    - **/status/system/services/traffic_class/state**  
      State.

  - **/status/system/services/httpserver**  
    HTTP server service.
    - **/status/system/services/httpserver/state**  
      State.

  - **/status/system/services/loadbalance**  
    WAN load balancing service.
    - **/status/system/services/loadbalance/state**  
      State.

  - **/status/system/services/routing**  
    Routing service.
    - **/status/system/services/routing/state**  
      State.

  - **/status/system/services/ippt**  
    IP pass-through service or related.
    - **/status/system/services/ippt/state**  
      State.

  - **/status/system/services/stats**  
    Statistics collection service.
    - **/status/system/services/stats/state**  
      State.

  - **/status/system/services/dyndns**  
    Dynamic DNS service.
    - **/status/system/services/dyndns/state**  
      State.

  - **/status/system/services/dnsmasq**  
    DNS caching/forwarding service.
    - **/status/system/services/dnsmasq/state**  
      State.

  - **/status/system/services/fullntp**  
    Full NTP service.
    - **/status/system/services/fullntp/state**  
      State.

  - **/status/system/services/ntp**  
    Basic NTP service.
    - **/status/system/services/ntp/state**  
      State.

  - **/status/system/services/ntpfailover**  
    NTP failover service.
    - **/status/system/services/ntpfailover/state**  
      State.

  - **/status/system/services/rollback**  
    System rollback service.
    - **/status/system/services/rollback/state**  
      State.

  - **/status/system/services/sdwan**  
    SD-WAN service.
    - **/status/system/services/sdwan/state**  
      State.

  - **/status/system/services/vpn**  
    VPN service.
    - **/status/system/services/vpn/state**  
      State.

  - **/status/system/services/eztun**  
    Possibly Ez-Tunnel service.
    - **/status/system/services/eztun/state**  
      State.

  - **/status/system/services/wan_bonding**  
    WAN bonding service.
    - **/status/system/services/wan_bonding/state**  
      State.

  - **/status/system/services/internalsvcs**  
    Internal services aggregator.
    - **/status/system/services/internalsvcs/state**  
      State.

  - **/status/system/services/adc**  
    ADC (Analog-to-Digital Converter) service.
    - **/status/system/services/adc/state**  
      State.

  - **/status/system/services/base_applications**  
    Base applications manager.
    - **/status/system/services/base_applications/state**  
      State.

  - **/status/system/services/cpmodem_airgain_http**  
    Specialized modem service (Airgain?).
    - **/status/system/services/cpmodem_airgain_http/state**  
      State.

  - **/status/system/services/at_passthrough**  
    AT command passthrough service.
    - **/status/system/services/at_passthrough/state**  
      State.

  - **/status/system/services/client_usage**  
    Tracks client usage data.
    - **/status/system/services/client_usage/state**  
      State.

  - **/status/system/services/csterm**  
    Possibly a terminal service for CS.
    - **/status/system/services/csterm/state**  
      State.

  - **/status/system/services/hwsensors**  
    Hardware sensors service.
    - **/status/system/services/hwsensors/state**  
      State.

  - **/status/system/services/ipfec**  
    IP forward error correction service.
    - **/status/system/services/ipfec/state**  
      State.

  - **/status/system/services/ips**  
    Intrusion prevention service or inspector.
    - **/status/system/services/ips/state**  
      State.

  - **/status/system/services/multicast**  
    Multicast handling service.
    - **/status/system/services/multicast/state**  
      State.

  - **/status/system/services/upgradetimeout**  
    Upgrade timeout manager.
    - **/status/system/services/upgradetimeout/state**  
      State.

  - **/status/system/services/opennhrp**  
    NHRP service (Dynamic multipoint VPN?).
    - **/status/system/services/opennhrp/state**  
      State.

  - **/status/system/services/pkt_loss_cnt**  
    Packet loss counting service.
    - **/status/system/services/pkt_loss_cnt/state**  
      State.

  - **/status/system/services/silentboot**  
    Silent boot service (no console output?).
    - **/status/system/services/silentboot/state**  
      State.

  - **/status/system/services/sms_service**  
    SMS sending/receiving service.
    - **/status/system/services/sms_service/state**  
      State.

  - **/status/system/services/snmpd**  
    SNMP daemon/service.
    - **/status/system/services/snmpd/state**  
      State.

  - **/status/system/services/usbupgrade**  
    USB-based firmware upgrade service.
    - **/status/system/services/usbupgrade/state**  
      State.

  - **/status/system/services/usbpassthrough**  
    USB pass-through service.
    - **/status/system/services/usbpassthrough/state**  
      State.

  - **/status/system/services/virtual_modem**  
    Virtual modem service.
    - **/status/system/services/virtual_modem/state**  
      State.

  - **/status/system/services/vrrp**  
    VRRP (Virtual Router Redundancy) service.
    - **/status/system/services/vrrp/state**  
      State.

  - **/status/system/services/link_monitor**  
    Monitors link status.
    - **/status/system/services/link_monitor/state**  
      State.

  - **/status/system/services/ConfigurableGPIO**  
    Configurable GPIO service.
    - **/status/system/services/ConfigurableGPIO/state**  
      State.

  - **/status/system/services/plugmod**  
    Plug-in modem service.
    - **/status/system/services/plugmod/state**  
      State.

  - **/status/system/services/sms_direct_service**  
    Direct SMS service.
    - **/status/system/services/sms_direct_service/state**  
      State.

  - **/status/system/services/ecm**  
    Enhanced connection manager or ECM?
    - **/status/system/services/ecm/state**  
      State.

  - **/status/system/services/ipverify**  
    IP verification service.
    - **/status/system/services/ipverify/state**  
      State.

  - **/status/system/services/l2tp**  
    L2TP VPN service.
    - **/status/system/services/l2tp/state**  
      State.

  - **/status/system/services/serialservice**  
    Serial interface service.
    - **/status/system/services/serialservice/state**  
      State.

  - **/status/system/services/sshserialservice**  
    SSH-over-serial or serial-SSH bridging service.
    - **/status/system/services/sshserialservice/state**  
      State.

  - **/status/system/services/obd**  
    OBD (on-board diagnostics?) service.
    - **/status/system/services/obd/state**  
      State.

  - **/status/system/services/modbusgateway**  
    Modbus gateway service.
    - **/status/system/services/modbusgateway/state**  
      State.

  - **/status/system/services/serialip**  
    Serial-over-IP service.
    - **/status/system/services/serialip/state**  
      State.

  - **/status/system/services/bouncemgr**  
    Possibly a network interface bounce manager.
    - **/status/system/services/bouncemgr/state**  
      State.

  - **/status/system/services/devicedisc**  
    Device discovery service.
    - **/status/system/services/devicedisc/state**  
      State.

  - **/status/system/services/gps**  
    GPS service.
    - **/status/system/services/gps/state**  
      State.

  - **/status/system/services/nemopmipv6**  
    NEMO or PMIPv6 service.
    - **/status/system/services/nemopmipv6/state**  
      State.

  - **/status/system/services/flowstats**  
    Flow statistics service.
    - **/status/system/services/flowstats/state**  
      State.

  - **/status/system/services/remote_modem_controller**  
    Remote control of modems.
    - **/status/system/services/remote_modem_controller/state**  
      State.

  - **/status/system/services/static_multicast**  
    Static multicast management service.
    - **/status/system/services/static_multicast/state**  
      State.

  - **/status/system/services/span**  
    Possibly a port mirroring or spanning service.
    - **/status/system/services/span/state**  
      State.

  - **/status/system/services/license**  
    License management service.
    - **/status/system/services/license/state**  
      License state.
    - **/status/system/services/license/base**  
      Base license info.

- **/status/system/accessories**  
  Info about connected accessories.

  - **/status/system/accessories/0**  
    First accessory slot (others omitted).
    - **/status/system/accessories/0/type**  
      Type of accessory.
    - **/status/system/accessories/0/desc**  
      Accessory description.
    - **/status/system/accessories/0/present**  
      Indicates if accessory is present.

- **/status/system/rtc**  
  Real-time clock info.

- **/status/system/available_ports**  
  Ports available on the system.
  - **/status/system/available_ports/0**  
    First port (others omitted).

- **/status/system/uptime**  
  System uptime.

- **/status/system/load_avg**  
  Load averages.

  - **/status/system/load_avg/1min**  
    1-minute average.
  - **/status/system/load_avg/5min**  
    5-minute average.
  - **/status/system/load_avg/15min**  
    15-minute average.

- **/status/system/cpu**  
  CPU usage metrics.

  - **/status/system/cpu/user**  
    CPU user time.
  - **/status/system/cpu/nice**  
    CPU nice time.
  - **/status/system/cpu/system**  
    CPU system time.

- **/status/system/interrupts**  
  Interrupts count.

- **/status/system/context_switches**  
  Context switches count.

- **/status/system/memory**  
  Detailed memory usage info.

  - **/status/system/memory/memtotal**  
    Total memory.
  - **/status/system/memory/memfree**  
    Free memory.
  - **/status/system/memory/memavailable**  
    Available memory.
  - **(…various fields for buffers, cached, swap, etc. omitted here for brevity but are present…)**

- **/status/system/time**  
  Current system time.

- **/status/system/wan_signal_strength**  
  WAN signal strength value.

- **/status/system/threads**  
  Running threads info.

  - **/status/system/threads/0**  
    First thread (others omitted).
    - **/status/system/threads/0/name**  
      Thread name.
    - **/status/system/threads/0/ident**  
      Thread identifier.

- **/status/system/apps**  
  System apps list.

  - **/status/system/apps/0**  
    First app entry.
    - **/status/system/apps/0/app**  
      Details of the app.
      - **/status/system/apps/0/app/uuid**  
        App UUID.
      - **/status/system/apps/0/app/name**  
        App name.
      - **/status/system/apps/0/app/date**  
        Install/build date.
      - **/status/system/apps/0/app/restart**  
        Restart needed?
      - **/status/system/apps/0/app/reboot**  
        Reboot needed?
      - **/status/system/apps/0/app/auto_start**  
        Auto-start config.
      - **/status/system/apps/0/app/vendor**  
        Vendor name.
      - **/status/system/apps/0/app/version_major**  
        Major version.
      - **/status/system/apps/0/app/version_minor**  
        Minor version.
      - **/status/system/apps/0/app/version_patch**  
        Patch version.
    - **/status/system/apps/0/state**  
      Current state.
    - **/status/system/apps/0/summary**  
      Summary info.

- **/status/system/sdk**  
  SDK or extension system.

  - **/status/system/sdk/service**  
    SDK service status.
  - **/status/system/sdk/summary**  
    Summary info.
  - **/status/system/sdk/mode**  
    Operating mode.
  - **/status/system/sdk/apps**  
    SDK applications list (not expanded).

- **/status/system/sensors**  
  Sensor data.

  - **/status/system/sensors/level**  
    Sensor level.
  - **/status/system/sensors/day**  
    Daytime sensor readings.
    - **/status/system/sensors/day/high**  
      High reading.
    - **/status/system/sensors/day/low**  
      Low reading.

- **/status/system/fw_upgrade_timeout**  
  Firmware upgrade timeout value.

- **/status/system/serial**  
  System serial interface data.

  - **/status/system/serial/status**  
    Serial status.
  - **/status/system/serial/modbus**  
    Modbus data (not expanded).
  - **/status/system/serial/serial_ip**  
    Serial over IP data (not expanded).

- **/status/system/commands**  
  System commands interface.

- **/status/system/boot**  
  Boot details.

---

## /status/mount

- **/status/mount**  
  File system mount info.

- **/status/mount/filesystem**  
  Filesystem specifics.

- **/status/mount/disk_usage**  
  Disk usage stats.
  - **/status/mount/disk_usage/total_bytes**  
    Total disk size.
  - **/status/mount/disk_usage/free_bytes**  
    Free disk space.

---

## /status/usb

- **/status/usb**  
  USB subsystem info.

- **/status/usb/connection**  
  Overall USB connection.
  - **/status/usb/connection/state**  
    State of the USB connection.

- **/status/usb/int1**  
  First USB interface.
  - **/status/usb/int1/state**  
    Interface state.
  - **/status/usb/int1/type**  
    Interface type.

---

## /status/security

- **/status/security**  
  Security data.

- **/status/security/default_password**  
  Default password info.
  - **/status/security/default_password/admin**  
    Admin default password details.
  - **/status/security/default_password/wifi**  
    Wi-Fi default password details.

- **/status/security/ips**  
  Intrusion Prevention System details.
  - **/status/security/ips/signature_version**  
    Signature version info.
    - **/status/security/ips/signature_version/major**  
      Major signature version.
    - **/status/security/ips/signature_version/minor**  
      Minor signature version.
  - **/status/security/ips/engine_version**  
    IPS engine version.
    - **/status/security/ips/engine_version/major**  
      Major engine version.
    - **/status/security/ips/engine_version/minor**  
      Minor engine version.
    - **/status/security/ips/engine_version/rev**  
      Revision number.
  - **/status/security/ips/last_updated**  
    Date/time of last update.
  - **/status/security/ips/sigIds**  
    Signature IDs list (omitted).
  - **/status/security/ips/ips_info**  
    Additional IPS info.

---

## /status/fw_info

- **/status/fw_info**  
  Firmware info.

- **/status/fw_info/major_version**  
  Major firmware version.

- **/status/fw_info/minor_version**  
  Minor firmware version.

- **/status/fw_info/patch_version**  
  Patch firmware version.

- **/status/fw_info/build_date**  
  Firmware build date.

- **/status/fw_info/build_version**  
  Build version info.

- **/status/fw_info/build_type**  
  Build type (release, debug, etc.).

- **/status/fw_info/fw_update_available**  
  Indicates if a firmware update is available.

- **/status/fw_info/upgrade_major_version**  
  Major version of available upgrade.

- **/status/fw_info/upgrade_minor_version**  
  Minor version of available upgrade.

- **/status/fw_info/upgrade_patch_version**  
  Patch version of available upgrade.

- **/status/fw_info/sign_cert_types**  
  Signature certificate types info.

- **/status/fw_info/fw_release_tag**  
  Firmware release tag.

- **/status/fw_info/manufacturing_upgrade**  
  Manufacturing upgrade info.

- **/status/fw_info/multi_images**  
  Support for multiple firmware images.

---

## /status/product_info

- **/status/product_info**  
  Device product info.

- **/status/product_info/mac0**  
  Primary MAC address.

- **/status/product_info/company_name**  
  Company/manufacturer name.

- **/status/product_info/company_url**  
  Company URL.

- **/status/product_info/product_name**  
  Product name.

- **/status/product_info/copyright**  
  Copyright text.

- **/status/product_info/soc_serial**  
  SoC serial number.

- **/status/product_info/features**  
  Feature flags (not expanded).

- **/status/product_info/has_activation_key**  
  Whether device requires an activation key.

- **/status/product_info/activation_key_verify**  
  Activation key verification details.
  - **/status/product_info/activation_key_verify/uuid**  
    Key’s UUID.
  - **/status/product_info/activation_key_verify/matches**  
    Whether key matches.

- **/status/product_info/manufacturing**  
  Manufacturing details.
  - **/status/product_info/manufacturing/board_ID**  
    Board ID.
  - **/status/product_info/manufacturing/mftr_date**  
    Manufacturing date.
  - **/status/product_info/manufacturing/serial_num**  
    Serial number.

---

## /status/wlan

- **/status/wlan**  
  WLAN subsystem status.

- **/status/wlan/state**  
  WLAN state.

- **/status/wlan/debug**  
  Debug info for WLAN.
  - **/status/wlan/debug/state**  
    Debug state.

- **/status/wlan/radio**  
  Radio information (multiple radios).

  - **/status/wlan/radio/0**  
    First radio (others omitted).
    - **/status/wlan/radio/0/channel**  
      Current channel.
    - **/status/wlan/radio/0/channel_contention**  
      Contention data.
    - **/status/wlan/radio/0/channel_list**  
      Possible channels.
      - **/status/wlan/radio/0/channel_list/0**  
        First channel listed (others omitted).
    - **/status/wlan/radio/0/channel_locked**  
      Indicates if channel is locked.
    - **/status/wlan/radio/0/reconnecting**  
      Reconnect state.
    - **/status/wlan/radio/0/region_code**  
      Region code.
    - **/status/wlan/radio/0/survey**  
      Survey info (detailed, not expanded).
    - **/status/wlan/radio/0/clients**  
      Connected clients on this radio.
    - **/status/wlan/radio/0/bss**  
      BSS listings.
      - **/status/wlan/radio/0/bss/0**  
        First BSS (others omitted).
        - **/status/wlan/radio/0/bss/0/bssid**  
          BSSID address.
        - **/status/wlan/radio/0/bss/0/info_element**  
          Info elements.
          - **/status/wlan/radio/0/bss/0/info_element/audit**  
            Audit data.
    - **/status/wlan/radio/0/txpower**  
      Transmit power.

- **/status/wlan/remote**  
  Remote WLAN data.
  - **/status/wlan/remote/radio/0**  
    First remote radio info (survey, etc.).

- **/status/wlan/region**  
  Region info.
  - **/status/wlan/region/version**  
    Region version.
  - **/status/wlan/region/country_code**  
    Country code.
  - **/status/wlan/region/override**  
    Whether override is in use.
  - **/status/wlan/region/reboot_needed**  
    If a reboot is needed after region change.
  - **/status/wlan/region/global_wifi**  
    Global Wi-Fi mode.
  - **/status/wlan/region/regions_supported**  
    Array of supported regions.
    - **/status/wlan/region/regions_supported/0**  
      First region name (others omitted).
  - **/status/wlan/region/safe_mode**  
    Safe mode setting.
  - **/status/wlan/region/mobile**  
    Mobile setting.

- **/status/wlan/events**  
  WLAN events.
  - **/status/wlan/events/associate**  
    Association event.
  - **/status/wlan/events/disassociate**  
    Disassociation event.
  - **/status/wlan/events/timeout**  
    Timeout event.
  - **/status/wlan/events/deauthenticated**  
    Deauthentication event.
  - **/status/wlan/events/mac_filter_allow**  
    MAC filter allow event.
  - **/status/wlan/events/mac_filter_deny**  
    MAC filter deny event.

- **/status/wlan/trace**  
  Trace logs array.
  - **/status/wlan/trace/0**  
    First trace entry (others omitted).

- **/status/wlan/clients**  
  WLAN clients list (not expanded).

---

## /status/signal_strength_leds

- **/status/signal_strength_leds**  
  LED controls for signal strength.

---

## /status/wan

- **/status/wan**  
  WAN subsystem info.

- **/status/wan/stats**  
  Overall WAN statistics.
  - **/status/wan/stats/bps**  
    Bits per second (TX?).
  - **/status/wan/stats/collisions**  
    Collision count.
  - **/status/wan/stats/ibps**  
    Bits per second incoming.
  - **/status/wan/stats/idrops**  
    Incoming drops.
  - **/status/wan/stats/ierrors**  
    Input errors.
  - **/status/wan/stats/imcasts**  
    Incoming multicasts.
  - **/status/wan/stats/in**  
    Bytes in.
  - **/status/wan/stats/ipackets**  
    Incoming packets.
  - **/status/wan/stats/noproto**  
    Unknown protocol count.
  - **/status/wan/stats/obps**  
    Bits per second outgoing.
  - **/status/wan/stats/oerrors**  
    Output errors.
  - **/status/wan/stats/omcasts**  
    Outgoing multicasts.
  - **/status/wan/stats/opackets**  
    Outgoing packets.
  - **/status/wan/stats/out**  
    Bytes out.
  - **/status/wan/stats/ts**  
    Timestamp of these stats.

- **/status/wan/swans**  
  Possibly a SWANS policy or engine.

  - **/status/wan/swans/cm/priority**  
    Priority info.

  - **/status/wan/swans/history**  
    History of WAN states.

  - **/status/wan/swans/dataused**  
    Data usage breakdown.
    - **/status/wan/swans/dataused/wandevs**  
      WAN devices usage.
    - **/status/wan/swans/dataused/updaters**  
      Updater processes?

- **/status/wan/connection_state**  
  Overall connection state (text or code).

- **/status/wan/ipinfo**  
  IP configuration.
  - **/status/wan/ipinfo/primary**  
    Primary IP or interface.
  - **/status/wan/ipinfo/gateway**  
    Gateway address.
  - **/status/wan/ipinfo/ip_address**  
    WAN IP address.
  - **/status/wan/ipinfo/netmask**  
    WAN netmask.
  - **/status/wan/ipinfo/dns**  
    DNS servers.
    - **/status/wan/ipinfo/dns/0**  
      First DNS address.

- **/status/wan/ip6info**  
  IPv6 config (not expanded).

- **/status/wan/policies**  
  WAN policy manager.
  - **/status/wan/policies/policies**  
    Collection of named policies.
    - **/status/wan/policies/policies/SwansEnginePolicy**  
      SWANS engine policy.
      - **/status/wan/policies/policies/SwansEnginePolicy/enabled**  
        Whether enabled.
      - **/status/wan/policies/policies/SwansEnginePolicy/state**  
        Policy state.
    - **/status/wan/policies/policies/Unready**  
      Another policy (enabled, state).
    - **/status/wan/policies/policies/LinkWentDown**, etc.  
      Additional policy nodes (similar structure).
    - **(…many policy entries each with “enabled” and “state”…)**

  - **/status/wan/policies/primary**  
    Primary policy info.

- **/status/wan/primary_device**  
  Indicates which WAN device is primary.

- **/status/wan/cm**  
  Connection manager reference.

- **/status/wan/devices**  
  WAN device collection.

  - **/status/wan/devices/ethernet-wan**  
    Ethernet WAN device.
    - **/status/wan/devices/ethernet-wan/info**  
      Device info (MAC, manufacturer, etc.).
      - **/status/wan/devices/ethernet-wan/info/port_name/0**  
        First port name (others omitted).
    - **/status/wan/devices/ethernet-wan/stats**  
      Packet/byte stats, errors, etc.
    - **/status/wan/devices/ethernet-wan/status**  
      Link state, reason codes, summary, etc.
      - **/status/wan/devices/ethernet-wan/status/link_flags/0**  
        First link flag (others omitted).
    - **/status/wan/devices/ethernet-wan/connectors**  
      Physical connectors info (not expanded).
    - **/status/wan/devices/ethernet-wan/config**  
      Configuration parameters (DHCP, NAT, etc.).
      - **/status/wan/devices/ethernet-wan/config/6rd/ipv4_common_prefix**  
        6RD prefix.
      - **/status/wan/devices/ethernet-wan/config/auto6/pd_reqlen**  
        IPv6 PD request length.
      - **/status/wan/devices/ethernet-wan/config/bandwidth_egress**  
        Egress bandwidth limit.
      - **/status/wan/devices/ethernet-wan/config/bandwidth_ingress**  
        Ingress bandwidth limit.
      - **/status/wan/devices/ethernet-wan/config/def_conn_state**  
        Default connection state.
      - **/status/wan/devices/ethernet-wan/config/disabled**  
        Whether device is disabled.
      - **/status/wan/devices/ethernet-wan/config/failback**  
        Failback config (times, modes).
        - **/status/wan/devices/ethernet-wan/config/failback/exclude_sibling**  
          Exclude sibling device.
        - **/status/wan/devices/ethernet-wan/config/failback/mode**  
          Failback mode.
        - **/status/wan/devices/ethernet-wan/config/failback/rate_bandwidth**  
          Data rate threshold.
        - **/status/wan/devices/ethernet-wan/config/failback/rate_time**  
          Rate-time threshold.
        - **/status/wan/devices/ethernet-wan/config/failback/time**  
          Time-based failback.
      - **/status/wan/devices/ethernet-wan/config/failureCheck**  
        Failure detection settings.
        - **/status/wan/devices/ethernet-wan/config/failureCheck/idle_seconds**  
          Idle threshold.
        - **/status/wan/devices/ethernet-wan/config/failureCheck/mode**  
          Check mode.
        - **/status/wan/devices/ethernet-wan/config/failureCheck/retry_count**  
          Retry attempts.
        - **/status/wan/devices/ethernet-wan/config/failureCheck/retry_interval**  
          Retry interval.
      - **/status/wan/devices/ethernet-wan/config/failureCheck6**  
        IPv6 failure check settings (similar).
      - **/status/wan/devices/ethernet-wan/config/force_nat**  
        Force NAT usage.
      - **/status/wan/devices/ethernet-wan/config/hostname**  
        Hostname for DHCP client.
      - **/status/wan/devices/ethernet-wan/config/ip4_mode**  
        IPv4 mode (DHCP, static).
      - **/status/wan/devices/ethernet-wan/config/ip6_mode**  
        IPv6 mode.
      - **/status/wan/devices/ethernet-wan/config/ip_mode**  
        Combined IP mode.
      - **/status/wan/devices/ethernet-wan/config/modem**  
        Modem-specific settings (for bridging?).
      - **/status/wan/devices/ethernet-wan/config/name**  
        Display name.
      - **/status/wan/devices/ethernet-wan/config/net_name**  
        Possibly user-defined network name.
      - **/status/wan/devices/ethernet-wan/config/priority**  
        Priority of this WAN device.
      - **(…many more config fields under /ethernet-wan/config…)**

  - **/status/wan/devices/mdm-9a724d09**  
    Example cellular modem device.
    - **/status/wan/devices/mdm-9a724d09/info**  
      Modem info: type, model, firmware, capabilities.
      - **/status/wan/devices/mdm-9a724d09/info/carrier_images**  
        Multiple carrier images.
        - **/status/wan/devices/mdm-9a724d09/info/carrier_images/0**  
          First carrier image (others omitted).
      - **/status/wan/devices/mdm-9a724d09/info/router_images**  
        Router images for this modem.
        - **/status/wan/devices/mdm-9a724d09/info/router_images/0**  
          First image (others omitted).
      - **/status/wan/devices/mdm-9a724d09/info/firmware_images**  
        Stored firmware images.
        - **/status/wan/devices/mdm-9a724d09/info/firmware_images/0**  
          First firmware image info (others omitted).
      - **/status/wan/devices/mdm-9a724d09/info/profiles**  
        APN profiles for cellular.
        - **/status/wan/devices/mdm-9a724d09/info/profiles/0**  
          First profile (others omitted).
      - **/status/wan/devices/mdm-9a724d09/info/supports_activation**  
        Whether the modem supports activation.
      - **/status/wan/devices/mdm-9a724d09/info/mfg_model**  
        Manufacturer model name.
      - **/status/wan/devices/mdm-9a724d09/info/pri_id**  
        PRI ID (carrier provisioning).
      - **/status/wan/devices/mdm-9a724d09/info/pri_ver**  
        PRI version.
      - **(…other flags about GPS, remote upgrade, multi firmware, etc. …)**

    - **/status/wan/devices/mdm-9a724d09/stats**  
      Modem traffic stats.
    - **/status/wan/devices/mdm-9a724d09/status**  
      Modem status (link state, summary, reason).
      - **/status/wan/devices/mdm-9a724d09/status/link_flags/0**  
        First link flag (others omitted).
      - **/status/wan/devices/mdm-9a724d09/status/idle**  
        Whether device is idle.
      - **/status/wan/devices/mdm-9a724d09/status/idle_check**  
        Idle-check details.
        - **/status/wan/devices/mdm-9a724d09/status/idle_check/history**  
          History of idle-check results.
      - **(…truncated here as file ends…)**

---

**End of file snippet**  
(Additional lines may exist beyond the truncation point.)

