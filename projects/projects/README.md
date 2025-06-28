# Cybersecurity Projects

This section demonstrates my practical engagement across SOC tiers — from log monitoring to malware analysis and threat hunting — as part of my transition into a SOC Manager and future CISO role.

---

## 🏗️ SOC Home Lab Environment (In Progress)

A purpose-built, virtual Security Operations Center designed for skill development across:

- **Tier 1:** Monitoring and Alert Triage  
- **Tier 2:** Incident Investigation and Malware Analysis  
- **Tier 3:** Threat Hunting and Forensics

### 🧰 Lab Setup Summary

- **Host Hardware:** Predator i9 Laptop (32GB RAM, 500GB SSD)
- **Hypervisor:** VMware Workstation Pro
- **Network Type:** VMware NAT (isolated lab with internet access)

### 💻 Virtual Machines

| VM | OS | Role | Tools |
|----|----|------|-------|
| VM1 | Ubuntu 20.04 | Wazuh Server | SIEM for log ingestion, correlation, alerting |
| VM2 | Ubuntu 20.04 | Endpoint | Simulated attack target (e.g., SSH brute force) |
| VM3 | REMnux | Malware Analysis | YARA, Volatility, Cuckoo Sandbox |
| VM4 | Ubuntu 20.04 | TheHive | Case and incident response management |

### 🧪 Additional Tools on Host (Windows 11)

- **Wireshark** – Network traffic capture and packet analysis  
- **OBS Studio** – Demo recording and walkthrough documentation  

---

## 🔍 Project Objectives

- Simulate cyber attacks and monitor them in real-time via Wazuh
- Analyze captured malware using REMnux and Cuckoo Sandbox
- Generate, triage, and escalate alerts using TheHive
- Correlate system logs, detect anomalies, and map activity to **MITRE ATT&CK**
- Document response workflows, timelines, and artifact handling

> 📝 Additional documentation, screenshots, configs, and demo videos will be uploaded progressively.
