# task-1-port-scan
Task 1: Scan Your Local Network for Open Ports.
Task - Open Port Scanning with Nmap

**Objective**
Discover open ports on devices within a local network to understand network exposure and potential risks.

**Tools Used**
- [Nmap] (https://nmap.org/download.html) – Free and open-source network scanner  

**Steps Followed**

1. **Installed Nmap** from the official website.
2. **Identified Local Network Range**  
   - Found local IP address using `ipconfig` (Windows) or `ifconfig` (Linux/macOS).  
   - Determined subnet: `192.168.1.0/24`
3. **Ran TCP SYN Scan** using the following command:
   ```bash
   nmap -sS 192.168.1.0/24
4. Recorded Open Ports & Active IP Addresses
   Noted all devices with open ports.
5. Analyzed Services
   Used Nmap documentation and internet research to identify common services running on detected ports.
6. Identified Security Risks
   Highlighted potential vulnerabilities based on open services.
7. Saved Scan Results
   Used this command to save scan output:
   bash
   nmap -sS 192.168.1.0/24 -oN scan_results.txt
