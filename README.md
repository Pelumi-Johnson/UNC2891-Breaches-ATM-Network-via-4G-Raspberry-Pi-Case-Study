# 🏧 UNC2891 Breaches ATM Network via 4G Raspberry Pi – Case Study


[![UNC2891 ATM Breach – Preview](https://github.com/Pelumi-Johnson/UNC2891-Breaches-ATM-Network-via-4G-Raspberry-Pi-Case-Study/blob/main/Screenshot%202026-01-15%20214506.png)](./LuGeSTA.pdf)

This presentation analyzes a highly sophisticated attack attributed to **UNC2891 (LightBasin)**, in which attackers physically implanted a 4G-enabled Raspberry Pi into an ATM network to bypass perimeter defenses and deploy the CAKETAP rootkit for attempted financial fraud.

## 🔍 Incident Overview

![Badge](https://img.shields.io/badge/Incident%20Analysis-Physical%20Intrusion%20%7C%20Advanced%20Malware-yellow?style=for-the-badge)

---
- Threat actor UNC2891 targeted financial institutions using a blend of **physical access** and **custom malware**
- Objective was to spoof Hardware Security Module (HSM) messages to authorize fraudulent ATM withdrawals
- Attack was detected and disrupted before any funds were stolen

## 🧠 Attack Mechanics
- Raspberry Pi 4 with 4G modem planted directly into ATM network switch
- Cellular connectivity bypassed internal firewalls and monitoring
- Remote access maintained via TinyShell backdoor and dynamic DNS
- Lateral movement enabled persistence even after device removal

## 🧬 Malware & Stealth Techniques
- Deployment of **CAKETAP rootkit**, disguised as a legitimate system service
- Use of Linux bind mounts to hide malicious processes
- Technique aligns with **MITRE ATT&CK T1564.013 (Hide Artifacts)**

## ⚠️ Why This Matters
- Demonstrates how physical access can completely undermine strong network defenses
- Highlights gaps in monitoring for rogue hardware and wireless signals
- Shows the evolving sophistication of financially motivated threat actors

## 🛡️ Defensive Lessons
- Restrict and monitor physical access to ATM hardware and network switches
- Deploy RF detection for unauthorized wireless devices
- Use tamper-evident seals, surveillance, and regular inspections
- Treat physical security as a core component of cybersecurity strategy

## 📂 Presentation
📄 Full presentation available as a PDF documenting the attack chain, technical techniques, and key defensive lessons.
