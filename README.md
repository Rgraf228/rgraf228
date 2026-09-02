## Hi, I’m Russell 👋

I’m a security-focused IT professional building hands-on SOC projects, home labs, and investigation writeups.  
I work with Wazuh SIEM, pfSense, and Proxmox to practice threat detection, incident response, and security operations in a realistic lab environment.  

I’m currently preparing for CompTIA Network+ and planning Security+ next, with the goal of moving into NOC, SOC, or IT operations roles.

## What I’m Working On
- Expanding my Wazuh SIEM lab with additional Windows & Linux endpoints  
- Building structured SOC investigation writeups based on real alerts  
- Strengthening networking fundamentals (VLANs, routing, firewall rules)  
- Practicing threat hunting and log analysis across multiple data sources  
- Preparing for CompTIA Network+ (exam scheduled Aug 2026)

## Certifications & Learning
- CompTIA Network+ — Aug 2026   
- CompTIA Security+ — Aug 2026

## Skills
**Security & SOC**
- SIEM (Wazuh)
- Log analysis & alert triage
- Threat detection & investigation
- MITRE ATT&CK mapping
- Endpoint hardening (CIS Benchmarks)

**Networking & Systems**
- TCP/IP, VLANs, firewall rules (pfSense)
- Virtualization (Proxmox)
- Windows & Linux administration
- Basic scripting (Python)

**Tools & Platforms**
- Wazuh SIEM stack
- pfSense firewall
- Proxmox virtualization
- Ubuntu Server

## 🧪 Home Lab Environment
I operate a full security-focused home lab designed to simulate SOC, NOC, and IT operations workflows.  
It allows me to practice threat detection, log analysis, network segmentation, and incident investigation in a realistic environment.

### Core Components
- **Proxmox Virtualization Server** — Hosts multiple Linux and Windows VMs for endpoint monitoring, testing, and analysis.
- **pfSense Firewall** — Provides VLAN segmentation, routing, firewall rules, and network isolation for controlled security testing.
- **Wazuh SIEM/XDR Stack** — Centralized log collection, file integrity monitoring, security configuration assessment, and alerting.
- **Ubuntu Server** — Used for log forwarding, agent testing, and running lightweight services.
- **Windows 11 Endpoint** — Enrolled into Wazuh for monitoring authentication events, PowerShell activity, and system changes.

### What I Practice in This Lab
- **Log analysis & alert triage** using Wazuh dashboards and rule-based detections  
- **Threat detection** across Windows and Linux endpoints  
- **Network segmentation** with pfSense VLANs and firewall policies  
- **Endpoint hardening** using CIS Benchmarks and SCA results  
- **Investigation workflows** modeled after SOC analyst practices  
- **Documentation & writeups** for CVEs, suspicious activity, and MITRE ATT&CK techniques  

### Lab Goals
- Build realistic SOC-style investigations  
- Strengthen networking fundamentals  
- Improve detection engineering skills  
- Expand automation using Python  


## 🔍 Featured Security Investigations

These are some of my most detailed and representative SOC-style investigations.  
Each one includes detection, research, investigation steps, remediation, and lessons learned.

### **[Windows Logon Success Alert Triage](ca://s?q=Tell_me_more_about_Windows_Logon_Success_Triage)**
**Skills:** Log analysis, authentication event triage, MITRE ATT&CK mapping  
**Tools:** Wazuh SIEM, Windows Event Logs  
**Summary:** Investigated repeated successful logon events to determine whether they indicated normal user behavior, credential misuse, or lateral movement.

### **[Git Credential Helper Carriage Return Confusion (CVE-2024-52006)](ca://s?q=Tell_me_more_about_CVE_2024_52006)**
**Skills:** Vulnerability analysis, exploit reproduction, secure configuration  
**Tools:** Wazuh, Git, Linux  
**Summary:** Analyzed a Git credential parsing flaw that could lead to misinterpreted authentication data and insecure credential handling.

### **[Vite Arbitrary File Read via WebSocket fetchModule Bypass (CVE-2026-39368)](ca://s?q=Tell_me_more_about_CVE_2026_39368)**
**Skills:** Web security, file read exploitation, threat modeling  
**Tools:** Linux, Vite dev server, Wazuh log monitoring  
**Summary:** Demonstrated how malformed WebSocket requests could bypass file access restrictions and expose sensitive files.

### **[node-tar Path Traversal Cluster](ca://s?q=Tell_me_more_about_node_tar_CVE_cluster)**
**Skills:** Path traversal exploitation, filesystem security, remediation planning  
**Tools:** Linux, node-tar, Wazuh  
**Summary:** Investigated multiple related CVEs involving symlink/hardlink traversal that could lead to arbitrary file write or overwrite.

### **[Steam Client Registry Permission Weakness (CVE-2019-14743)](ca://s?q=Tell_me_more_about_CVE_2019_14743)**
**Skills:** Windows registry analysis, privilege escalation research  
**Tools:** Windows 11, Wazuh, MITRE ATT&CK  
**Summary:** Explored how weak registry permissions could allow unauthorized modification of Steam client settings.

📁 Full repository: [Security Writeups](https://github.com/Rgraf228/Security-writeups)

## 📫 Contact
- Email: russell.graf228@gmail.com  
- LinkedIn: https://www.linkedin.com/in/russell-graf/  
- GitHub: https://github.com/Rgraf228



