# dd-wrt-utilities

Set of utilities that can be used to make using and managing dd-wrt (https://dd-wrt.com/) just a little bit easier.

- <b>fix_vap_vlan</b> - identifies the Wi-Fi interfaces that should be restarted post-reboot when running Virtual Access Points associated with custom VLANs
- <b>vlan_check</b> - verifies VLAN-relevant NVRAM variables are set consistently with each other when configuring VLANs using the technique described at https://wiki.dd-wrt.com/wiki/index.php/Switched_Ports#NVRAM_variables--defining_the_switch_and_VLANS
- <b>wifi_list</b> - lists Ethernet, Wi-Fi, MAC, bridge, VLAN and SSID details for each configured wireless network

These scripts were only tested on Broadcom-based routers (mainly Asus RT-AC68U) but would likely work on other types of router running dd-wrt.
