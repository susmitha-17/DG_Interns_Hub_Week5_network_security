# 04 – Burp Suite

This folder contains the screenshots and evidence from the **web application traffic interception and HTTP request analysis** performed using Burp Suite during the Week 5 VAPT practical.

Burp Suite Community Edition was used as an intercepting proxy to observe and analyze HTTP communication between the browser and the authorized Ubuntu Apache web server. The activity helped understand how web browsers send HTTP requests and how request headers provide information about the client and the requested resource.

### Target

- Target IP: `192.168.56.101`
- Target URL: `http://192.168.56.101`
- Web Server: Apache 2.4.66 (Ubuntu)
- Protocol: HTTP
- Port: `80/tcp`

### Proxy Configuration

Burp Suite proxy listener:

```text
127.0.0.1:8080
