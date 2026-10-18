## Hi, I'm Russell 👋

**Networking & Security | CompTIA Network+ and Security+ | Home lab builder | Python automation**

I'm an IT professional with a software development background, moving into network engineering. I build segmented lab networks, monitor them, break them, and document what I learn.

## 🎯 What I'm Working On
- Studying for the **Cisco CCNA**
- Building out VLAN segmentation, inter-VLAN routing, and firewall policy in my home lab
- Integrating pfSense logging into my Wazuh SIEM for network visibility
- Writing up troubleshooting sessions and investigations in a structured format

## 📜 Certifications
- CompTIA Network+ (Aug 2026)
- CompTIA Security+ (Aug 2026)

## 🧪 Home Lab
A segmented lab for practicing networking, monitoring, and security operations.

- **Proxmox** hosting Linux and Windows VMs
- **pfSense** providing routing, VLAN segmentation, DHCP, and firewall rules between network zones
- **Managed switch** with 802.1Q VLANs and STP tuning (Portfast/edge ports)
- **Wazuh SIEM/XDR** collecting logs and alerts from Windows and Linux endpoints
- **Ubuntu Server** and **Windows 11** endpoints for agent testing and monitoring

**What I practice here**
- VLAN design and inter-VLAN firewall policy
- Network troubleshooting (DHCP conflicts, STP port flapping, packet loss)
- Log analysis and alert triage
- Endpoint hardening with CIS Benchmarks
- Python scripting for security and network tooling

📁 *Lab documentation and topology diagrams: [link to homelab-network repo]*

## 🛠️ Skills
**Networking**
- TCP/IP, DHCP, DNS
- VLANs / 802.1Q, STP
- Firewall rules and segmentation (pfSense)
- Packet analysis (Wireshark)

**Systems & Automation**
- Proxmox virtualization
- Windows & Linux administration
- Python, JavaScript

**Security**
- SIEM (Wazuh), alert triage, log analysis
- Vulnerability research and remediation
- MITRE ATT&CK mapping, CIS Benchmarks

## 🔍 Featured Investigations
Security write-ups following a Detection → Research → Investigation → Remediation → Lessons Learned format.

- **[Windows Logon Success Alert Triage](LINK-TO-FILE)** – Determined whether repeated successful logons were normal behavior, credential misuse, or lateral movement (Wazuh, Windows Event Logs)
- **[Vite Arbitrary File Read (CVE-2026-39368)](LINK-TO-FILE)** – Analyzed a WebSocket bypass that exposed sensitive files
- **[node-tar Path Traversal Cluster](LINK-TO-FILE)** – Investigated related symlink/hardlink CVEs and planned remediation

📁 Full repository: [Security Writeups](https://github.com/Rgraf228/Security-writeups)
