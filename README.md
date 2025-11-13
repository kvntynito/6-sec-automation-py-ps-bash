## Cybersecurity Automation & Scripting

This project showcases practical cybersecurity automation across Python, PowerShell, and Bash.
It includes tools for log parsing, alert generation, evidence collection, and security task automation used in real SecOps, SOC, and Incident Response environments.

## 🎯 Objectives

- Build cross-platform automation tools
- Parse and normalize logs (Windows, Linux, Sysmon)
- Automate alerting and enrichment
- Detect suspicious patterns with scripting
- Create reusable SOC/IR utilities

## 📁 What’s Inside
- docs/       - Script explanations, usage, templates
- scripts/    - Python, PowerShell, Bash automation tools
- lab/        - Sample logs, test datasets, script outputs
- .github/    - Issue/PR templates

## 🧪 Lab Setup (Quick Start)
You can run everything on:
- Windows 10/11
- Linux (Ubuntu/Debian/CentOS)
- WSL
- A VM environment
- Azure VM (optional)

**Required tools**

- Python 3.10+
- PowerShell 7+ or Windows PowerShell
- Bash (Linux or WSL)

Scripts are designed to run locally, so no special infrastructure is needed.

## ⚙️ Automation Focus Areas
🐍 **Python Automation**
- Log parsing & normalization
- Detect suspicious patterns
- IP enrichment (GeoIP, AbuseIPDB, VirusTotal)
- JSON event parsing
- Automated reporting (CSV → HTML → Markdown)
- Regex pattern matching
- Simple threat detection scripts

🪟 **PowerShell Automation (Windows)**
- Check for failed logins
- Parse Windows Event Logs
- Export security logs
- ASR & Defender status checks
- Sysmon evidence collection
- RDP brute-force detection

🐧 **Bash Automation (Linux)**
- Review SSH logs
- File integrity checks
- UFW/iptables verifications
- auditd checks
- Parsing /var/log/auth.log
- Detect suspicious commands
- User/permission auditing

## ▶️ How to Run Scripts (Examples)
**Python**

python3 scripts/python/TEMPLATE_log_parser.py sample.log

**PowerShell**

pwsh scripts/powershell/TEMPLATE_failed_login_detector.ps1

**Bash**

bash scripts/bash/TEMPLATE_update_audit.sh


Replace target filenames as needed.

## 📊 Deliverables
✅ Python log parser

✅ PowerShell Windows event analyzer

✅ Bash Linux auditing script

✅ Sample logs for testing (lab/)

✅ Documentation for how each script works

✅ Evidence of successful execution

## 🧠 What I Learned
- Bullet points of concepts/skills you gained - Write what you learned about Python, PowerShell, parsing logs.
- How to automate repetitive security tasks
- How SIEMs normalize logs (because I simulated it manually)
- Regex + pattern matching for threat detection
- How to parse Windows, Linux, and Sysmon logs
- How scripting improves SOC efficiency
- How automation supports incident response
- How to enrich logs with external intelligence sources

## ✅ Next Steps
- Add a full Python tool to detect brute-force attacks
- Add a PowerShell script to export Sysmon logs + compress
- Add a Bash script to check Linux hardening status
- Add a simple REST API script to query VirusTotal
- Build a CLI menu-based Python security toolkit
- Combine scripts into a small “automation suite”

## Related Projects

🛡️ Repo 1 – Sentinel Detection Engineering
Use automation to generate or enrich detection datasets.
https://github.com/kvntynito/1-secops-detentions-sentinel

🔎 Repo 2 – Vulnerability Management
Automate scan data parsing and risk classification.
https://github.com/kvntynito/2-vuln-mgmt-openvas-lab

## ⚖️ License
MIT – see `LICENSE`.
