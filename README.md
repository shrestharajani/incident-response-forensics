# 🕵️‍♀️ Incident Response & Forensic Analysis – Metasploitable 3 (Ubuntu)

## 📌 Overview
This project replicates a realistic cyber attack on a vulnerable Metasploitable 3 machine, followed by a full forensic investigation. It demonstrates exploitation, post-exploitation activities, and in-depth memory, disk, and network analysis using open-source tools.

📎 📁 Full documentation available in the `docs` folder:  
📄 [`incident-response-report.pdf`](./docs/Incident_Response_Forensics_Final.pdf)

---

## 🎯 Objectives
- Simulate a real-world cyber attack using a known vulnerability (ProFTPD mod_copy)
- Perform detailed forensic analysis on captured memory, disk images, and network traffic
- Reconstruct the attack timeline, identify attacker actions, and propose mitigations

---

## 🛠️ Tools & Technologies Used

| Category               | Tools Used                                              |
|------------------------|----------------------------------------------------------|
| Reconnaissance & Exploitation | Nmap, Metasploit, Kali Linux                       |
| Network Forensics      | Security Onion, CyberChef, Kibana                       |
| Memory Forensics       | Volatility 3                                            |
| Disk Forensics         | Autopsy                                                 |
| Virtualization         | VMWare, Metasploitable 3 (Ubuntu)                       |

---

## 🔍 Highlights

- ✅ Simulated attack using ProFTPD mod_copy exploit
- ✅ Conducted memory dump analysis with Volatility to identify malicious processes
- ✅ Analyzed disk image using Autopsy to recover bash history and unauthorized file access
- ✅ Investigated network traffic with Security Onion and visualized findings in Kibana
- ✅ Documented attack timeline and key indicators of compromise (IOCs)

---

## 📘 Key Takeaways

- How to simulate and execute a real-world cyber attack in a controlled lab environment
- Techniques for capturing and analyzing volatile memory (RAM) using Volatility 3
- Practical disk forensics and file system reconstruction using Autopsy
- Deepened understanding of attacker behaviors, including:
  - Privilege escalation
  - Persistence mechanisms
  - Data exfiltration techniques
- Learned to detect and analyze network anomalies using Security Onion and visualize IOCs with Kibana
- Strengthened documentation and reporting skills for structured forensic reports

---

## ✅ Project Status
- ✅ Completed  
- 🗓️ Date: April 2024  
- 🔒 Confidentiality: Educational purposes only  
