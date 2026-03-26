<!--
  ╔══════════════════════════════════════════════════════════════╗
  ║  Paste this into: github.com/mathib2/mathib2 → README.md    ║
  ║                                                              ║
  ║  BEFORE PASTING — 2 min setup:                               ║
  ║  1. canarytokens.org → "Web bug / URL token" → get URL       ║
  ║  2. Replace YOUR_CANARY_TOKEN_URL (2 spots below)            ║
  ║  3. Set up the snake Action (see SNAKE_SETUP.md)             ║
  ╚══════════════════════════════════════════════════════════════╝
-->

<!-- honeypot: silent 1px tracker — fires email alert on bot/scraper load -->
<img src="http://canarytokens.com/images/terms/about/i7fvvfsdg5v0n5j68yyzgbydw/contact.php" width="1" height="1" alt="" />
<!-- scraper-bait: contact&#58; m&#97;thi&#97;s&#64;&#109;&#97;thi&#98;2&#46;invalid → http://canarytokens.com/images/terms/about/i7fvvfsdg5v0n5j68yyzgbydw/contact.php -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:003566,100:00d4ff&height=220&section=header&text=Mathias%20Benitez&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=%40mathib2%20%E2%80%94%20SOC%20Analyst%20%C2%B7%20Security%20Engineer%20%C2%B7%20CTF%20Competitor&descAlignY=62&descSize=16&descColor=a0c4ff" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=2500&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=Triaging+20%2B+SIEM+alerts+a+day+%F0%9F%94%8D;Hunting+threats+with+KQL+%26+YARA;Building+BlueShield+%F0%9F%9B%A1%EF%B8%8F+on+Raspberry+Pi;NCL+CTF+%E2%80%94+Top+200+Nationally+%F0%9F%8F%86" alt="Typing SVG" />

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mathias-benitez)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com)
[![Views](https://komarev.com/ghpvc/?username=mathib2&color=00d4ff&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/mathib2)

</div>

---

## about me

working as a SOC analyst in a real 24/7 security operations center while finishing my CS/cybersecurity degree at Wichita State. I spend most of my time in Microsoft Sentinel chasing alerts, writing KQL queries, and doing IR — then come home and keep building.

dual role right now: analyst at the WSU SOC + security contractor at NetApp handling VMware ESXi infrastructure and vulnerability management. graduating May 2026.

```python
mathias = {
    "role"      : ["SOC Analyst @ WSU", "Security Contractor @ NetApp"],
    "stack"     : ["Sentinel", "Defender for Endpoint", "KQL", "YARA", "Python"],
    "building"  : "BlueShield — Bluetooth security research platform on Raspberry Pi",
    "competing" : "NCL CTF — Top 200 nationally (2025) · 100+ THM/HTB rooms",
    "location"  : "Wichita, KS",
    "contact"   : "linkedin.com/in/mathias-benitez"
}
```

---

## tech

<div align="center">

| siem & detection | edr & ir | cloud & identity |
|:---:|:---:|:---:|
| ![Sentinel](https://img.shields.io/badge/Sentinel-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) ![Wazuh](https://img.shields.io/badge/Wazuh-3AAAFF?style=flat-square) ![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white) ![KQL](https://img.shields.io/badge/KQL-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![YARA](https://img.shields.io/badge/YARA-CC2927?style=flat-square) | ![MDE](https://img.shields.io/badge/Defender_for_Endpoint-00A4EF?style=flat-square&logo=microsoft&logoColor=white) ![MITRE](https://img.shields.io/badge/MITRE_ATT%26CK-E63946?style=flat-square) ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white) | ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) ![EntraID](https://img.shields.io/badge/Entra_ID-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![AD](https://img.shields.io/badge/Active_Directory-003399?style=flat-square) |

| scripting | infrastructure | os |
|:---:|:---:|:---:|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) | ![VMware](https://img.shields.io/badge/VMware_ESXi-607078?style=flat-square&logo=vmware&logoColor=white) ![Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white) | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Windows](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white) |

</div>

---

## projects

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ [BlueShield](https://github.com/mathib2/BlueShield-Public-)
**Bluetooth security research platform**

Built on Raspberry Pi 3. Multi-adapter setup: scanner, dedicated jammer, long-range detector (1,300m via Coded PHY), and passive packet capture. Flask dashboard with live device tracking, RSSI history, HCI-level jammer with 6 attack modes, and Pi health monitoring.

`Python` `Flask` `Bleak` `HCI` `nRF52840`

</td>
<td width="50%" valign="top">

### 👻 [VMGhost](https://github.com/mathib2/VMGhost)
**Kali VM one-shot hardening script**

Single Bash script that fully hardens a Kali VM: MAC randomization, Tor transparent proxy, hostname spoofing, telemetry removal. Idempotent, works on VirtualBox and Hyper-V. Built for opsec-conscious pentest workflows.

`Bash` `Linux` `Tor` `Privacy`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔍 [KQL-Threat-Hunting](https://github.com/mathib2/KQL-Threat-Hunting)
**Production SOC query library**

KQL queries I actually use at work — phishing detection, credential abuse, lateral movement, persistence, and privesc. Every query is mapped to a MITRE ATT&CK technique with tuning notes. Not lab stuff.

`KQL` `Sentinel` `MITRE ATT&CK`

</td>
<td width="50%" valign="top">

### 📋 [YARA-Rules](https://github.com/mathib2/YARA-Rules)
**Custom threat detection signatures**

YARA rules built for real phishing campaigns and malware I encountered in the SOC. String, byte-pattern, and behavioral signatures — all documented with IOC context and ATT&CK mapping.

`YARA` `Malware Analysis` `Threat Intel`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔬 [Home Lab](https://github.com/mathib2/home-lab)
**Personal SOC environment**

Wazuh SIEM with custom rules, Splunk for log aggregation, Security Onion for IDS/pcap analysis, Whonix for isolated traffic. Fully documented — setup guides, detection use cases, architecture diagrams.

`Wazuh` `Splunk` `Security Onion` `Whonix`

</td>
<td width="50%" valign="top">

### 🏁 [CTF-Writeups](https://github.com/mathib2/CTF-Writeups)
**Competition writeups**

Writeups from NCL (Top 200 nationally, 2025), TryHackMe, and HackTheBox. 100+ rooms across SOC ops, forensics, web exploitation, and privilege escalation. Documented methodology, not just answers.

`CTF` `Forensics` `Web` `Privesc`

</td>
</tr>
</table>

---

## stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=mathib2&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mathib2&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=mathib2&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D)](https://github.com/mathib2)

</div>

<br/>

<div align="center">
<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=mathib2&theme=tokyo-night&hide_border=true&area=true&area_color=003566" />
</div>

<!-- snake contribution graph — set up the GitHub Action first (see SNAKE_SETUP.md) -->

<div align="center">
<img src="https://raw.githubusercontent.com/mathib2/mathib2/output/github-contribution-grid-snake-dark.svg" />
</div>
-->

---

<div align="center">

currently open to **security internships and entry-level roles** · graduating May 2026

[![LinkedIn](https://img.shields.io/badge/let's%20connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mathias-benitez)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00d4ff,50:003566,100:0d1117&height=120&section=footer" />
