<!--
  ╔══════════════════════════════════════════════════════════════════╗
  ║  GitHub Profile README for @mathib2 — Mathias R. Benitez        ║
  ║  Copy this entire file content into:                             ║
  ║  github.com/mathib2/mathib2/blob/main/README.md                 ║
  ║  (Create a repo named exactly "mathib2" — same as your username) ║
  ╚══════════════════════════════════════════════════════════════════╝
-->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=800&color=00D4FF&center=true&vCenter=true&width=750&lines=Hey%2C+I'm+Mathias+%F0%9F%91%8B;SOC+Analyst+%7C+Security+Engineer;Threat+Hunter+%7C+Incident+Responder;Building+BlueShield+%F0%9F%9B%A1%EF%B8%8F+%7C+CTF+Competitor" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mathias%20Benitez-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mathias-benitez)
[![Email](https://img.shields.io/badge/Email-mathiasb020%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mathiasb020@gmail.com)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-100%2B%20Rooms-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com)
[![NCL](https://img.shields.io/badge/NCL%20CTF-Top%20200%20Nationally%20%F0%9F%8F%86-gold?style=for-the-badge)](https://nationalcyberleague.org)

</div>

---

## 👾 About Me

I'm a **cybersecurity professional** and May 2026 graduate at Wichita State University with **4+ years of real-world experience** across SOC operations, enterprise infrastructure, and security engineering. I currently hold dual roles:

- 🔵 **Junior InfoSec Analyst** at WSU's 24/7 Security Operations Center — triaging 20+ Microsoft Sentinel SIEM alerts daily, hunting threats with KQL, remediating 30–60 phishing attacks per day, and executing endpoint isolation with Microsoft Defender for Endpoint.
- 🟢 **Security & QA Contractor** at NetApp — administering enterprise storage infrastructure, developing Python automation tools, and performing NIST-aligned vulnerability management across VMware ESXi environments.

I don't just study security — I operate in it every day.

```python
class Mathias:
    location     = "Wichita, KS"
    role         = ["SOC Analyst", "Security Engineer", "CTF Player"]
    soc_stack    = ["Microsoft Sentinel", "Defender for Endpoint", "KQL", "YARA"]
    scripting    = ["Python", "PowerShell", "Bash"]
    currently    = "Building BlueShield — a Bluetooth security research platform"
    graduating   = "May 2026 · B.S. Cybersecurity · CS Minor"
    languages    = ["English (C1)", "Spanish (Native)"]
    cert_soon    = "CompTIA Security+ (May 2026)"
```

---

## 🛠️ Tech Stack

**SIEM & Detection**

![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-3AAAFF?style=flat-square&logo=wazuh&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Security Onion](https://img.shields.io/badge/Security_Onion-1A1A2E?style=flat-square)
![KQL](https://img.shields.io/badge/KQL-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![YARA](https://img.shields.io/badge/YARA-CC2927?style=flat-square)

**EDR & Incident Response**

![Defender for Endpoint](https://img.shields.io/badge/Defender_for_Endpoint-00A4EF?style=flat-square&logo=microsoft&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-E63946?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=portswigger&logoColor=white)

**Scripting & Automation**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Cloud & Identity**

![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Azure AD](https://img.shields.io/badge/Azure_AD_%2F_Entra_ID-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-003399?style=flat-square&logo=windows&logoColor=white)

**Infrastructure & Virtualization**

![VMware](https://img.shields.io/badge/VMware_ESXi-607078?style=flat-square&logo=vmware&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)

---

## 🚀 Featured Projects

### 🛡️ [BlueShield](https://github.com/mathib2/BlueShield-Public-) — Bluetooth Security Research Platform
> *Python · Flask · Bleak · HCI Sockets · Raspberry Pi*

A full-stack Bluetooth security platform built for cybersecurity research and education. Runs on Raspberry Pi with multi-adapter hardware support.

- Real-time BLE + Classic Bluetooth scanner with multi-adapter orchestration (scanner/jammer/long-range roles)
- Web dashboard (Flask + SocketIO) with live device tracking, manufacturer resolution, RSSI history, and threat classification
- HCI-level BLE jammer with 6 attack modes: flood, deauth, sweep, reactive, targeted, continuous
- Sniffle/nRF52840 integration for promiscuous BLE packet capture; Coded PHY (LE Long Range) for 1,300m detection range
- Pi 3 performance-optimized: throttled analysis pipeline, capped snapshot buffer, background health monitoring

---

### 👻 [VMGhost](https://github.com/mathib2/VMGhost) — Kali VM Privacy Hardening Script
> *Bash · Linux · Tor · Privacy Engineering*

Automated one-shot hardening script for Kali Linux VMs used in penetration testing environments.

- MAC address randomization, Tor transparent proxy routing, hostname spoofing, and system telemetry disabling
- Designed for opsec-conscious red team and CTF workflows
- Idempotent — safe to re-run; verified across VirtualBox and Hyper-V environments

---

### 🔬 [Home Lab](https://github.com/mathib2/home-lab) — Enterprise SOC Environment (Local)
> *Wazuh · Splunk · Security Onion · Whonix · VirtualBox · Hyper-V*

A production-grade home SOC lab documenting architecture, configurations, and detection use cases.

- Deployed Wazuh SIEM with endpoint agents, custom detection rules, and alert tuning
- Integrated Splunk for log aggregation and Security Onion for network IDS/packet analysis
- Whonix workstation + gateway for isolated anonymized traffic analysis
- Fully documented with architecture diagrams, setup guides, and detection playbooks

---

### 🔍 [KQL-Threat-Hunting](https://github.com/mathib2/KQL-Threat-Hunting) — Production KQL Query Library
> *KQL · Microsoft Sentinel · MITRE ATT&CK*

A curated library of KQL queries written and used in a live 24/7 SOC environment, mapped to MITRE ATT&CK techniques.

- Covers: phishing detection, credential abuse, lateral movement, persistence mechanisms, privilege escalation
- Each query includes ATT&CK tactic/technique mapping, description, and tuning notes
- Battle-tested against real alerts — not lab-only queries

---

### 📋 [YARA-Rules](https://github.com/mathib2/YARA-Rules) — Custom Threat Detection Rules
> *YARA · Malware Analysis · Threat Intelligence*

Custom YARA rules developed to detect phishing campaigns and malware families encountered in SOC operations.

- Rules include string-based, byte-pattern, and behavioral signatures
- Documented with malware family, IOC context, and detection rationale
- Deployed in production against live endpoint telemetry

---

### 🏁 [CTF-Writeups](https://github.com/mathib2/CTF-Writeups) — Competition Writeups
> *CTF · Forensics · Web App · Privilege Escalation · Reverse Engineering*

Detailed writeups from TryHackMe, HackTheBox, and NCL competitions. 100+ rooms completed, NCL Top 200 nationally (2025).

- Categories: SOC operations, IR scenarios, forensics, web exploitation, privesc, OSINT
- Includes methodology, tooling, and key takeaways for each challenge
- Useful reference for interview prep and skill demonstration

---

## 🔭 What I'm Working On

- `BlueShield v5.x` — Adding nRF52840 long-range scanning (Coded PHY), Sniffle packet capture integration, and HackRF wideband RF jamming module
- `KQL-Threat-Hunting` — Publishing the full query library from my SOC work with ATT&CK mappings
- `CompTIA Security+` — Exam scheduled May 2026

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=mathib2&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mathib2&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=mathib2&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🎯 Competitive & Continuous Learning

| Platform | Activity |
|----------|----------|
| 🏆 NCL CTF | **Top 200 Nationally** (2025) |
| 💻 TryHackMe | **100+ rooms** — SOC, IR, Forensics, Web App, Privesc |
| 🔥 HackTheBox | Active — Web exploitation, AD attacks |
| 🎓 WSU | **Dean's Honor Roll** · B.S. Cybersecurity · CS Minor |

---

## 📫 Let's Connect

I'm open to **internships, entry-level security roles, and research collaborations** starting May 2026.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mathias-benitez)
[![Email](https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mathiasb020@gmail.com)

</div>

---

<div align="center">
<sub>🔐 Real experience. Real alerts. Real impact.</sub>
</div>
