# Network Discovery and Vulnerability Assessment with Nmap

## Project Overview

This project demonstrates the use of **Nmap (Network Mapper)** for network discovery, service enumeration, and vulnerability assessment. The goal is to showcase practical cybersecurity skills by identifying active hosts, discovering open ports, enumerating services, and assessing potential security risks within a network environment.

Through this project, I demonstrate my understanding of networking fundamentals, reconnaissance methodologies, and security assessment techniques commonly used by cybersecurity professionals during vulnerability assessments and penetration testing engagements.

---

## Objectives

- Discover active devices on a network.
- Identify open TCP/UDP ports.
- Enumerate running services and service versions.
- Perform operating system detection.
- Assess potential vulnerabilities using the Nmap Scripting Engine (NSE).
- Analyze and document findings in a professional format.
- Develop practical experience with network reconnaissance and attack surface identification.

---

## Skills Demonstrated

- Network Reconnaissance
- Host Discovery
- Port Scanning
- Service Enumeration
- Operating System Detection
- Vulnerability Assessment
- Attack Surface Analysis
- Security Reporting
- Linux Command Line Operations
- Cybersecurity Documentation

---

## Tools Used

- Nmap
- Nmap Scripting Engine (NSE)
- Kali Linux
- Wireshark 
- Terminal/Command Line Interface
---

## Methodology

1. Network Discovery
   - Identify live hosts within the target network.
     Network Range:192.168.1.198
     ```nmap -sn 192.168.1.0/24```
     <img width="581" height="793" alt="image" src="https://github.com/user-attachments/assets/9eb26879-fbcb-474e-8751-7e1640033ab2" />


2. Port Scanning
   - Discover open TCP and UDP ports.
   -  ```nmap -sS 192.168.1.198```
   -  <img width="876" height="344" alt="image" src="https://github.com/user-attachments/assets/92b12a93-01bc-4f95-bb93-4ab261f3ebb4" />

     

3. Service Enumeration
   - Detect service versions and configurations.
   - ```nmap -sV 192.168.1.198```

4. Operating System Detection
   - Identify operating systems and device types.
   - Analyze host characteristics.

5. Vulnerability Assessment
   - Utilize NSE scripts to identify known weaknesses.
   - Review potential security misconfigurations.

6. Documentation and Reporting
   - Record findings and observations.
   - Provide risk analysis and remediation recommendations.

---

## Project Structure

```text
├── scans/
│   ├── host-discovery/
│   ├── port-scans/
│   ├── service-enumeration/
│   └── vulnerability-scans/
│
├── reports/
│   ├── findings.md
│   ├── risk-analysis.md
│   └── recommendations.md
│
├── screenshots/
│
└── README.md
