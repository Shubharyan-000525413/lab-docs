# Security Investigation Portfolio – Lab Documentation  
Author: **Shubharyan Asthana**

This repository contains a collection of SOC (Security Operations Center)–oriented investigation reports created as part of **TryHackMe Advent of Cyber 2025**.

Each report follows real-world SOC Tier-1 → Tier-2 documentation standards, emphasizing accurate investigation workflows, evidence-driven analysis, and defensible conclusions. The portfolio demonstrates hands-on capability across SIEM investigations, web attack forensics, malware analysis, cloud alert triage, password cracking, and detection engineering, with consistent alignment to MITRE ATT&CK.

The complete portfolio is available as a GitHub Pages site:

👉 **https://shubharyan-000525413.github.io/lab-docs/**

---

## 🔹 Included Reports

### **1. Splunk Investigation – Web Application Compromise (Day 3)**  
A full end-to-end reconstruction of a web server compromise using Splunk.  
Includes:

- Spike and anomaly detection  
- Attacker fingerprinting  
- SQL injection & RCE reconstruction  
- C2 communication correlation  
- SPL query documentation  
- MITRE ATT&CK mapping  
- SOC remediation & detection engineering guidance  

📄 **View report:**  
`Splunk_Lab_Report.html`

---

### **2. Malware Analysis – HopHelper.exe (Day 6)**  
Static and dynamic malware analysis of a suspicious Windows executable delivered via phishing.

Includes:

- SHA256 hash fingerprinting  
- Strings and IOC discovery  
- Registry persistence analysis (Regshot)  
- Network behavior & outbound traffic (ProcMon)  
- Behavioral conclusions  
- MITRE ATT&CK mapping  

📄 **View report:**  
`Malware_Analysis.html`

---

### **3. Azure SOC Alert Triage – Microsoft Sentinel (“Tinsel Triage”) (Day 10)**  
A cloud-native SOC investigation using Microsoft Sentinel to analyze Linux PrivEsc alerts across multiple hosts.

Includes:

- Alert triage & prioritization  
- SIEM entity correlation  
- KQL queries for deep-dive log investigation  
- Detection of kernel module insertion, sudo abuse, Polkit exploitation attempts  
- Reverse shell activity identification  
- Lateral movement analysis  
- MITRE ATT&CK mapping  
- SOC remediation & detection engineering recommendations  

📄 **View report:**  
`Sentinel_Triage.html`

---

### **4. Password Cracking & Encrypted File Analysis (Day 9)**  
Hands-on analysis of weak password-protected PDF and ZIP files.

Includes:

- Dictionary-based cracking (pdfcrack, John the Ripper)  
- ZIP/PDF hash extraction  
- Offline attack surface analysis  
- SOC detection opportunities (process telemetry, GPU load, potfile events)  
- MITRE ATT&CK mapping  

📄 **View report:**  
`Password_Cracking.html`

---
### **5. Web Attack Forensics – Command Injection Investigation (Day 15)**

Splunk-based investigation of a web application command injection attack.

Includes:

Detection of malicious HTTP requests containing Base64-encoded payloads

Apache access and error log analysis

Correlation of web exploitation with Sysmon process creation events

Identification of OS-level command execution (cmd.exe, powershell.exe)

Attacker reconnaissance confirmation (whoami.exe)

Payload decoding and scope assessment

MITRE ATT&CK mapping and defensive recommendations

📄 **View report:**  
Splunk_Web_Forensics.html

## 🚀 How to View Reports

### **Method 1 — GitHub Pages (Recommended)**
Open the full, styled portfolio website:  
👉 **https://shubharyan-000525413.github.io/lab-docs/**  

Each report contains a dedicated button and is fully readable in-browser.

---

### **Method 2 — View HTML Files Directly**
You can also open the HTML files directly from the repository:

- `Splunk_Lab_Report.html`
- `Malware_Analysis.html`
- `Sentinel_Triage.html`
- `Password_Cracking.html`

If GitHub does not render the HTML preview, click **Raw** → Save → open in your browser.

---

## ⭐ About This Project  
These reports are intended for:

- Cybersecurity students  
- Entry-level to intermediate SOC analysts  
- Anyone learning Splunk, Sentinel, malware analysis, or threat detection  
- Recruiters & hiring managers evaluating technical capability and documentation skills  

The documentation structure matches real SOC workflows and demonstrates:

- Alert triage  
- Threat correlation  
- Forensics-style reconstruction  
- Detection engineering  
- MITRE ATT&CK alignment  

---

## 📬 Contact  
For collaboration or professional inquiries:

**LinkedIn:**  
https://www.linkedin.com/in/shubharyan-260102sa

---

Happy threat hunting! 🛡️🔍
