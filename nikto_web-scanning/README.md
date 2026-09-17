# 03 – Nikto Web Scanning

This folder contains the screenshots and scan output generated during the web server security assessment performed using **Nikto**.

Nikto was used to examine the authorized Ubuntu Apache web server for common security misconfigurations, missing HTTP security headers, information disclosure, and other potentially insecure web-server configurations.

### Target
- Target IP: `192.168.56.101`
- Target URL: `http://192.168.56.101`
- Web Server: Apache 2.4.66 (Ubuntu)
- Protocol: HTTP
- Port: `80/tcp`

### Tool Used
- Nikto 2.6.0

### Command Used

```bash
nikto -h http://192.168.56.101
