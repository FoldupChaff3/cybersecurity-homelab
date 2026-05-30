# Cybersecurity Home Lab

A personal cybersecurity lab built to develop hands-on skills in vulnerability exploitation, SIEM deployment, intrusion detection, and network segmentation. This lab simulates a small SOC environment using real tools and techniques aligned with industry standards.

---

## Hardware

- **Panasonic Toughbook FZ-55** — Primary lab machine
- **Hypervisor:** Proxmox VE 9.1

---

## Lab Phases

### ✅ Phase 1 — Vulnerability Exploitation (Complete)
- Deployed **Metasploitable 2** as a vulnerable target VM
- Performed host discovery and service enumeration using **Nmap**
- Exploited **CVE-2007-2447** (Samba usermap_script) via **Metasploit Framework**
- Obtained unauthenticated root shell on target machine
- Documented full attack chain from reconnaissance to post-exploitation

### 🔄 Phase 2 — SIEM & Intrusion Detection (In Progress)
- Deploying **Wazuh SIEM** on Ubuntu Server 22.04
- Integrating **Suricata IDS** for network traffic analysis
- Configuring **Cisco VLAN segmentation** to isolate lab network segments
- Goal: detect and alert on simulated attacks from Phase 1 techniques

---

## Skills Demonstrated

- Virtualization & hypervisor management (Proxmox)
- Vulnerability scanning and enumeration (Nmap)
- Exploitation framework usage (Metasploit)
- CVE research and application
- SIEM deployment and configuration (Wazuh)
- Intrusion detection (Suricata)
- Network segmentation (VLANs)

---

## Status

| Phase | Description | Status |
|-------|-------------|--------|
| Phase 1 | Vulnerability Exploitation | ✅ Complete |
| Phase 2 | SIEM + IDS + Network Segmentation | 🔄 In Progress |

---

## Disclaimer

This lab is fully isolated and used strictly for educational purposes. No techniques documented here are used against systems without authorization.
