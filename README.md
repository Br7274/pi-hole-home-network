# Pi-hole Home Network Setup
This project documents my setup of Pi-hole running on a Raspberry Pi Zero 2 W. It's configured as both a DNS server and DHCP server, blocking ads and trackers across my entire home network.

FEATURES:

- Pi-hole as DNS + DHCP server
- Network-wide ad and tracker blocking
- Running on Raspberry Pi Zero 2 W (headless)
- Clean logs, custom DNS records, and fast response

SETUP OVERVIEW
- Installed Raspberry Pi OS Lite
- Enabled SSH + Wi-Fi at boot
- Installed Pi-hole with default settings
- Configured static IP: 192.168.1.197
- Disabled DHCP on Fios router
- Enabled DHCP on Pi-hole

FUTURE PLANS
- Add Unbound for private DNS resolution
- Setup WireGuard VPN for remote ad-blocking
- Add to my IT portfolio
