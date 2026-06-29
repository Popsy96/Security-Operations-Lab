# Security Operations Lab

Hands-on SOC analyst portfolio — three self-built projects covering detection engineering, vulnerability assessment, and adversary emulation, built end-to-end in a home lab environment.

Built alongside the [TryHackMe SOC Level 1](https://tryhackme.com/path/outline/soclevel1) learning path. Pairs with my capstone project, [AU-Cyber-Threat-Intelligence](https://github.com/Popsy96/AU-Cyber-Threat-Intelligence) — that project maps real-world OSINT threat intel to MITRE ATT&CK; this lab proves I can take that same intelligence and operationalize it: detect it, validate it, and report on it.

---

## Projects

### 🔍 [01 — Home SOC Lab](./home-soc-lab/) `🟡 In Progress — 2/7`
A working SIEM environment — Windows endpoint + Sysmon, Ubuntu Splunk server, log forwarding, and custom SPL detections for brute-force authentication and obfuscated PowerShell execution. Includes a 3-panel detection dashboard.

**Stack:** VirtualBox · Splunk Enterprise · Sysmon · SPL

- [x] VirtualBox + Windows VM + Sysmon installed and logging
- [x] Splunk server VM running, accessible via web UI
- [ ] Universal Forwarder shipping logs successfully
- [ ] 2+ working detections (brute force, PowerShell) with saved alerts
- [ ] Dashboard with 3+ panels
- [ ] Screenshots captured for every key step
- [ ] README.md written and pushed

### 🛡️ [02 — Vulnerability Assessment Report](./vulnerability-assessment/) `⚪ Not Started — 0/6`
A pentest-style assessment of a deliberately vulnerable host — Nmap recon, OpenVAS scanning, manual CVSS v3.1 scoring, and a client-style remediation report.

**Stack:** Kali Linux · OpenVAS/Greenbone · Metasploitable 2 · CVSS v3.1

- [ ] Metasploitable 2 + Kali running in isolated network
- [ ] OpenVAS installed and scan completed
- [ ] Nmap recon results documented
- [ ] 5–8 findings manually CVSS-scored
- [ ] Full report written (exec summary → findings → remediation)
- [ ] Report PDF + README pushed

### 🎯 [03 — MITRE ATT&CK Threat Emulation](./mitre-attack-emulation/) `⚪ Not Started — 0/6`
Closing the loop: simulating real adversary techniques (T1110, T1059.001, T1053.005, T1003.001) inside the Home SOC Lab using Atomic Red Team, then validating whether the detections built in Project 1 actually catch them — including an honest coverage gap.

**Stack:** Atomic Red Team · Splunk · MITRE ATT&CK Navigator

- [ ] Invoke-AtomicRedTeam installed on lab Windows VM
- [ ] 3–4 ATT&CK techniques selected and emulated
- [ ] Corresponding Splunk detections written and validated
- [ ] Full kill chain documented for at least one technique
- [ ] Coverage table built (including at least one honest gap)
- [ ] README ties back to capstone CTI Dashboard work

---

## Overall Progress

`Home SOC Lab` 🟩🟩⬜⬜⬜⬜⬜ **2/7**
`Vulnerability Assessment` ⬜⬜⬜⬜⬜⬜ **0/6**
`MITRE ATT&CK Emulation` ⬜⬜⬜⬜⬜⬜ **0/6**

*Last updated: 29 June 2026*

---

## Why this lab exists

Most graduate portfolios show isolated exercises. This one shows a full lifecycle: **build the infrastructure → engineer detections → assess vulnerabilities → emulate real techniques → validate (or find gaps in) coverage** — the same intelligence-to-detection loop covered conceptually in my capstone, now running live.

---

## About

Built by **Poojit "Popsy" Kasina** — Master of Cybersecurity graduate (AAHE Melbourne), currently completing TryHackMe SOC Level 1 and pursuing SOC Analyst roles.

[LinkedIn](#) · [AU-Cyber-Threat-Intelligence (Capstone)](https://github.com/Popsy96/AU-Cyber-Threat-Intelligence)
