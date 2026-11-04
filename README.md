# DHCP Configuration Using Cisco Packet Tracer

## About the Project
This is my second networking project, where I configured a Cisco 2911 router to assign IP addresses automatically to computers using DHCP.

I built a simple network with one router, one switch, and three PCs. Instead of manually assigning IP addresses, I configured the router to handle the process.

## Devices Used
- Cisco 2911 Router
- Cisco 2960 Switch
- 3 PCs

## Network Information

| Configuration | Value |
|---|---|
| Network | 192.168.2.0/24 |
| Subnet Mask | 255.255.255.0 |
| Router IP | 192.168.2.1 |
| DNS Server | 8.8.8.8 |
| DHCP Pool | OFFICE_LAN |
| Excluded IPs | 192.168.2.1 - 192.168.2.10 |

## What I Did
- Connected the router, switch, and three PCs.
- Configured the router's GigabitEthernet0/0 interface.
- Created a DHCP pool named OFFICE_LAN.
- Reserved IP addresses for devices that may need static IPs.
- Configured the PCs to obtain their IP addresses automatically.
- Tested network connectivity using ping.

## What I Learned
While working on this project, I learned how DHCP works and how a router can automatically assign IP addresses to connected devices.

I also encountered an APIPA issue during configuration, which gave me an opportunity to practice troubleshooting and checking network settings.

## Skills Practiced
- Cisco Packet Tracer
- DHCP Configuration
- IPv4 Addressing
- Basic Subnetting
- Router and Switch Configuration
- Network Troubleshooting
- Ping Testing

## Project File
The `.pkt` file is included in this repository.

---

**Made as part of my hands-on networking practice.**
