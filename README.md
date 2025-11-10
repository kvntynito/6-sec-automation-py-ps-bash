# <Project Title>

This project showcases cybersecurity automation across multiple scripting languages.
It includes tools for log parsing, alert generation, evidence collection, and security task automation used in real SecOps, SOC, and IR workflows.

## 🎯 Objectives
- Python tools
- PowerShell scripts
- Bash automation
- Log parsers

## 📁 What’s Inside
- `docs/` – reports, playbooks, baselines, diagrams
- `scripts/` – Python/PowerShell/Bash utilities
- `lab/` – sample logs, datasets, IaC
- `.github/` – issue/PR templates

## 🧪 Lab Setup (Quick Start)
You can run everything on:
- Windows 10/11
- Linux (Ubuntu/Debian/CentOS)
- WSL
- A VM environment
- Azure VM (optional)

**Required tools**

✅ Python 3.10+

✅ PowerShell 7+ or Windows PowerShell

✅ Bash (Linux or WSL)

## ⚙️ Automation Focus Areas
✅ **Python Automation**
- Log parsing & normalization
- Detect suspicious patterns
- IP enrichment (GeoIP, AbuseIPDB, VirusTotal)
- JSON event parsing
- Automated reporting (CSV → HTML → Markdown)
- Regex pattern matching
- Simple threat detection scripts

✅ **PowerShell Automation (Windows)**
- Check for failed logins
- Parse Windows Event Logs
- Export security logs
- ASR & Defender status checks
- Sysmon evidence collection
- RDP brute-force detection

✅ **Bash Automation (Linux)**
- Review SSH logs
- File integrity checks
- UFW/iptables verifications
- auditd checks
- Parsing /var/log/auth.log
- Detect suspicious commands
- User/permission auditing

## ▶️ How to Run Scripts (Examples)
✅ **Python**

python3 scripts/python/TEMPLATE_log_parser.py sample.log

✅ **PowerShell**

pwsh scripts/powershell/TEMPLATE_failed_login_detector.ps1

✅ **Bash**

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

## ⚖️ License
MIT – see `LICENSE`.
