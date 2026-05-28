# Sreejith Reji — Cybersecurity Portfolio 👋

### MSc Cyber Security | CEH | CompTIA Security+ | SOC Analyst (L1)

---

## About Me

Cybersecurity professional transitioning into an active SOC analyst role. I hold a Masters degree in Cyber Security alongside industry certifications, and I am currently building hands-on skills in Python scripting, KQL, SPL, and SQL — applied directly to real SOC workflows including threat detection, log analysis, IOC enrichment, and security automation.

This portfolio documents that journey — every project here was built to solve a real problem I will face on the job.

---

## Certifications

| Certification | Issuer | Status |
|---|---|---|
| MSc Cyber Security | University | ✅ Completed |
| Certified Ethical Hacker (CEH) | EC-Council | ✅ Completed |
| CompTIA Security+ | CompTIA | ✅ Completed |
| CompTIA CySA+ | CompTIA | 📋 Planned |

---

## Projects

---

### 🔧 [soc-python-tools](https://github.com/SreejithReji/soc-python-tools)
Python scripts built for real SOC analyst workflows.

| Tool | What it does | Status |
|---|---|---|
| `ioc_checker.py` | Bulk IP enrichment via VirusTotal API — queries 70+ vendors | ✅ Complete |
| `log_analyser.py` | Firewall log parser with auto-generated alert reports | 🔨 In progress |
| `alert_triage.py` | Severity scoring and auto-classification from SIEM exports | 📋 Planned |
| `report_generator.py` | Automated shift handover report from alert data | 📋 Planned |
| `log_monitor.py` | Real-time log tail with rule-based alerting | 📋 Planned |
| `mini_soar.py` | Enrich alert → lookup IOCs → auto-create incident ticket | 📋 Planned |

**Skills demonstrated:** Python scripting, REST API integration, JSON parsing, log analysis, file I/O, security automation

---

### 📁 [soc-sample-logs](https://github.com/SreejithReji/soc-sample-logs)
500-line realistic log files simulating a complete SOC incident lifecycle — quiet baseline, active attack, breach, lateral movement, and data exfiltration.

| File | Type | Lines | Key incidents simulated |
|---|---|---|---|
| `firewall.log` | Perimeter firewall | 500 | Brute force, C2 traffic, lateral movement |
| `windows_event.csv` | Windows Security Event Log | 500 | Failed logons, account lockout, persistence, privilege escalation |
| `web_access.log` | Nginx web server | 500 | SQLi, XSS, path traversal, scanner tools |
| `dns.log` | DNS query log | 500 | C2 beaconing, DNS tunnelling, suspicious domains |
| `ids_alerts.log` | Snort IDS alerts | 500 | EternalBlue, Cobalt Strike, exfiltration, port scans |

**The incident story:** These logs tell one coherent attack — recon → brute force → initial access → lateral movement → persistence → exfiltration. Each file shows the same incident from a different sensor perspective.

**Skills demonstrated:** Understanding of attack lifecycle, log formats, threat indicators, MITRE ATT&CK phases

---

### 🔍 [kql-soc-queries](https://github.com/SreejithReji/kql-soc-queries)
Comprehensive KQL query library for Microsoft Sentinel and Defender XDR — beginner through advanced.

| Category | Queries | Highlights |
|---|---|---|
| Foundations | 5 | Syntax, filtering, aggregation, time ranges |
| Authentication | 6 | Brute force, impossible travel, after-hours logons |
| Network | 5 | C2 beaconing, DNS tunnelling, port scanning, exfiltration |
| Endpoint | 5 | PowerShell abuse, LOLBins, persistence, credential dumping |
| Threat Hunting | 5 | Ransomware, Cobalt Strike, MITRE ATT&CK mapping |
| Incident Response | 4 | User timeline, IP investigation, host investigation, IOC search |
| Dashboards | 3 | Daily overview, alert severity, shift handover |

**Skills demonstrated:** KQL query writing, Microsoft Sentinel, Defender XDR, threat detection, MITRE ATT&CK

---

### 🔎 [spl-soc-queries](https://github.com/SreejithReji/spl-soc-queries)
Comprehensive SPL query library for Splunk — beginner through advanced.

| Category | Queries | Highlights |
|---|---|---|
| Foundations | 5 | Syntax, stats, aggregation, time ranges |
| Authentication | 5 | Brute force, lockouts, privileged account monitoring |
| Network | 5 | C2 detection, DNS tunnelling, large transfers |
| Endpoint | 5 | Suspicious processes, PowerShell, Sysmon |
| Threat Hunting | 5 | LOLBins, ransomware, Cobalt Strike named pipes |
| Incident Response | 4 | User timeline, IP investigation, IOC search |
| Dashboards | 3 | Daily overview, notable alerts, shift handover |

**Skills demonstrated:** SPL query writing, Splunk ES, Sysmon analysis, detection engineering

---

## Technical Skills

### Security Operations
- SIEM analysis and alert triage — Microsoft Sentinel, Splunk
- Log analysis — Windows Event, firewall, web server, DNS, IDS/IPS
- Threat intelligence — IOC enrichment, VirusTotal, AbuseIPDB, Shodan
- Incident response — identification, containment, eradication, recovery, documentation
- Network security — TCP/IP, packet analysis, port analysis, protocol analysis
- Web application security — OWASP Top 10, SQLi, XSS, path traversal, CSRF
- Attack frameworks — MITRE ATT&CK, Cyber Kill Chain, Diamond Model
- Endpoint security — EDR analysis, process investigation, persistence mechanisms

### Query Languages
- **KQL** — Microsoft Sentinel and Defender XDR threat hunting and detection
- **SPL** — Splunk alert investigation, detection engineering, dashboards
- **SQL** — Security data analysis and investigation *(in progress)*

### Programming & Automation
- **Python** — security scripting, API integration, log parsing, automation
- **Regex** — pattern matching for log parsing and IOC extraction
- **Git & GitHub** — version control and portfolio management
- **Bash** — basic Linux command line and log navigation

### Tools & Platforms
- Microsoft Sentinel · Microsoft Defender XDR
- Splunk Enterprise · Splunk ES
- Wireshark · Nmap · Metasploit *(lab only)*
- VirusTotal API · AbuseIPDB · Shodan
- VS Code · Git

---

## Currently Learning

- 🐍 Python SOC automation — log parsers, IOC enrichers, report generators, mini SOAR
- 📊 pandas for large-scale alert data analysis
- 🔔 Automated alerting via Slack and email APIs
- 🎯 TryHackMe SOC Level 1 learning path
- 🗄️ SQL for security data investigation
- 📜 CompTIA CySA+ preparation

---

## Roadmap — Coming Soon

| Project | Description | Timeline |
|---|---|---|
| SQL Security Investigation Lab | SQL queries for security data, joins, subqueries, investigation workflows | Q2 2026 |
| Windows Event Log Notes | Comprehensive reference for all key Windows security event IDs | Q2 2026 |
| Alert Triage Tool | Python tool for severity scoring and auto-classification | Q2 2026 |
| Mini SOAR Script | End-to-end: enrich alert → lookup IOCs → auto-create ticket | Q3 2026 |
| Detection Rules Library | Custom detection rules for Sentinel and Splunk | Q3 2026 |

---

## Learning Philosophy

I have the theory — the MSc and certifications gave me a strong foundation in attack vectors, protocols, cryptography, and threat modelling. What I am building now is the ability to translate that knowledge into code and queries.

Every project in this portfolio was built to solve a specific SOC problem, not as an abstract exercise. By the time I start my SOC role I will have working tools I can use from day one.

---

## Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/sreejithreji)
- 🐙 [GitHub](https://github.com/SreejithReji)

---

*This portfolio is actively updated as new tools, queries, and learning milestones are completed.*
