# Oussama Belhane
### 🛡️ Cybersecurity Engineering Graduate (5th Year — EMSI) | Blue Team, SOC & Infrastructure Hardening

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/oussama-belhane-952534204/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat&logo=gmail)](mailto:oussama.belhane@gmail.com)
[![Target](https://img.shields.io/badge/Target-Stage%20PFE%202027-10B981?style=flat)]()

---

## 🎯 Profile Overview
Final-year Cybersecurity Engineering student at **EMSI Casablanca** specialized in **Defensive Security (Blue Team)**, **SOC Operations**, and **Detection Engineering**.

Experienced in analyzing intrusion telemetry (Windows EVTX, Sysmon, Suricata NIDS, PCAP), building automated response workflows in **Shuffle SOAR**, and auditing/hardening enterprise **Active Directory (ADCS, Kerberos, Tiering Model)** aligned with **MITRE ATT&CK** and **NIST SP 800-61**.

---

## 🚀 Flagship Engineering Projects

### 🛡️ [BehaviorShield — Lightweight EDR & Ransomware Detection Engine](https://github.com/OussamaBelhane/BehaviorShield)
> *Real-time behavioral ransomware containment agent written in Python.*
* **Heuristic Scoring Engine:** Correlates real-time process telemetry using an 8-rule heuristic model (Sysmon Event IDs 1 & 11, Shannon file entropy calculation, and Volume Shadow Copy tamper detection).
* **Automated Containment:** Immediately halts malicious process trees and isolates affected endpoints in under **1.0 second**.
* **Software Architecture:** Modular Python agent communicating with a Flask REST API alerting backend and an interactive React.js supervision dashboard.

### 🔑 [ADCS-Scanner — Active Directory Certificate Services Auditor & Hardening](https://github.com/OussamaBelhane/ADCS-Scanner)
> *Automated Active Directory PKI security auditor and blue team remediation tool.*
* **Proactive Security Audit:** Parses raw binary `nTSecurityDescriptor` (MS-DTYP) structures over LDAP using `ldap3` to detect vulnerable ESC1 certificate templates allowing SAN impersonation.
* **Rollback-Safe Remediation:** Automatically exports backup-verified PowerShell scripts to remediate misconfigured templates without disrupting production PKI services.
* **DevSecOps Integration:** Validated through comprehensive unit testing (`pytest`) and automated GitHub Actions CI/CD workflows.

### 🚨 [Simulation de Crise Cyber & Triage d'Incidents — EMSI × CyberSup Paris](https://github.com/OussamaBelhane)
> *National ransomware crisis simulation defending critical infrastructure (Score: 74%).*
* **Real-time Triage:** Analyzed 100+ alert injects under high pressure, correlating Windows EVTX system logs and Zscaler proxy traffic.
* **Kill-Chain Reconstruction:** Isolated patient-zero workstation (`FIN-112`), disproved threat actor exfiltration bluff (117.8 GB vs 300 GB claimed), and verified healthy air-gap backups.

---

## 🛠️ Core Technical Arsenal

| Domain | Technologies & Telemetry |
| :--- | :--- |
| **SOC Operations & NIDS** | Wazuh SIEM/XDR, Shuffle SOAR, Suricata (NIDS), Wireshark, Zeek |
| **Windows Telemetry (EVTX)** | Sysmon (IDs 1, 10, 11), Windows Security Logs (4624, 4625, 4672, 4768) |
| **Active Directory Security** | ADCS ESC1, Kerberos (AS-REQ / TGS-REQ), DACL / SACL, Tiering Model, GPO Hardening |
| **Tooling & Development** | Python (ldap3, Scapy, Pytest, Flask), PowerShell (AD Administration & Rollbacks), Bash |
| **DevSecOps & Environments** | Docker, Git, GitHub Actions, VMware Workstation / ESXi, Linux (Arch/Debian) |

---

## 🔬 Home Lab Infrastructure
* **Enterprise Domain:** Windows Server 2022 Forest Root Domain Controller + Enterprise Root Certification Authority (AD CS).
* **Sensor Network:** Isolated VMware virtual networks monitored via **Wazuh Agent** and **Suricata NIDS** promiscuous tap interfaces.
* **Automation Pipeline:** Self-hosted **Shuffle SOAR** executing automated webhook triage and Threat Intelligence API enrichment (VirusTotal, AbuseIPDB).

---

## 📬 Contact & Availability
* **Location:** Casablanca, Morocco 🇲🇦 (Mobilité Nationale & Internationale)
* **Goal:** Actively seeking a 6-month **PFE Internship (Feb – July 2027)** in SOC, Incident Response, or Defensive Engineering.
* **Email:** [oussama.belhane@gmail.com](mailto:oussama.belhane@gmail.com)
* **LinkedIn:** [linkedin.com/in/oussama-belhane](https://linkedin.com/in/oussama-belhane-952534204/)
