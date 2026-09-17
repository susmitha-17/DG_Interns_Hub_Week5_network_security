# 02 – Nmap Scanning

This folder contains the screenshots and supporting evidence from the network reconnaissance and service identification activities performed using **Nmap** during the Week 5 VAPT practical.

Nmap was used to identify accessible TCP ports, detect running services, determine service versions, and gather additional information about the authorized Ubuntu target system. Three different Nmap scanning techniques were performed to understand the target's network exposure and available web service.

### Target
- Target IP: `192.168.56.101`
- Target System: Ubuntu Linux
- Network: `192.168.56.0/24`
- Web Service: Apache HTTP Server
- Port Identified: `80/tcp`

### Tool Used
- Nmap 7.99

### Scans Performed

#### 1. SYN Scan

```bash
nmap -sS 192.168.56.101
