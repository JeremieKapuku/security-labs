# security-labs
This lab will be my journey into cybersecurity
[security-labs_README.md](https://github.com/user-attachments/files/22373258/security-labs_README.md)
# Security Labs & SOC Notes — Jeremie Kapuku

**Location:** Ottawa, ON  •  **Email:** mrjeremiekapuku@gmail.com  •  **Resume roles:** IT Support | Helpdesk (Tech-Heavy) | Security Analyst Intern | SOC Trainee | Junior Network Tech

> This repository collects my hands-on notes, small labs, and runbooks while I study cybersecurity and prepare for blue-team roles.

## 📁 Repo Structure
```
security-labs/
├─ README.md
├─ labs/
│  ├─ windows_fundamentals/
│  ├─ network_basics/
│  ├─ phishing_triage/
│  └─ siem_queries/
├─ scripts/
│  ├─ powershell/
│  └─ python/
├─ notes/
│  ├─ threat_notes/
│  └─ cve_summaries/
└─ docs/
   ├─ runbooks/
   └─ diagrams/
```

## 🔎 SIEM Queries (examples)
- Failed-logon spikes (by host, by user)
- New admin account created
- Suspicious PowerShell usage
- Rare outbound ports

I'll maintain **saved searches** and a short **"what good looks like"** section per query.

## 🧰 Scripts
- **PowerShell:** device posture collection, user/mailbox quick reports, basic remediation helpers
- **Python:** simple log parsing / CSV pivots

## 🛡️ Phishing Triage Checklist (draft)
1. Inspect sender domain & display name
2. Link inspection (hover + URLscan), attachment type
3. Look for urgency/financial lures
4. Check SPF/DKIM/DMARC results (if available)
5. User confirmation & ticket notes; escalate if indicators present

## 🗂️ Runbooks
- VPN failure triage (client-side)
- O365 mail flow checks (user-level)
- Account lockout SOP (AD + MFA)
- Phishing triage workflow

## 🎯 Training & Certifications (planned)
- CompTIA Security+ (SY0-701)
- CompTIA Network+
- Microsoft SC-900 (Security, Compliance, and Identity Fundamentals)
- Splunk Fundamentals 1 (free)
- TryHackMe: SOC Level 1 Learning Path
- TryHackMe rooms: Windows Fundamentals, Network Security, Phishing Analysis

> I’ll mark each item as completed with links to notes or labs as I progress.

## 🔗 How to Use
Clone the repo, then explore `labs/` for step-by-step exercises and `docs/runbooks` for quick triage guides.

---
_Updated: 2025-09-17_
