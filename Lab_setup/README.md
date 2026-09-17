# 01 – Lab Setup

This folder contains the screenshots and documentation related to the initial setup of the VAPT practical environment. The lab was configured using VirtualBox with Kali Linux as the security testing machine and Ubuntu Linux as the authorized target machine.

The Ubuntu VM was configured with an Apache2 web server and connected to Kali Linux through a VirtualBox Host-Only network. The target system was assigned the IP address `192.168.56.101`, while Kali Linux was configured on the same `192.168.56.0/24` network.

The connectivity between the Kali attacker machine and Ubuntu target was verified using ICMP ping before starting the Nmap, Nikto, and Burp Suite security testing activities.

This controlled lab environment was used to perform the Week 5 VAPT exercises safely and only against an authorized system.

### Lab Components
- Kali Linux – Testing/Attacker Machine
- Ubuntu Linux – Authorized Target Machine
- Apache2 – Web Server
- VirtualBox – Virtualization Platform
- Host-Only Network – `192.168.56.0/24`

### Target
- IP Address: `192.168.56.101`
- Web Service: Apache HTTP Server
- Port: `80/tcp`

### Evidence
- `Task1_Kali_Ubuntu_Connectivity.png` – Successful connectivity verification between Kali Linux and Ubuntu.
