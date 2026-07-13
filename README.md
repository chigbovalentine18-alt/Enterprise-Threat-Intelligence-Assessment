# 🛡️ Enterprise Threat Intelligence Assessment

---

## 📖 Project Overview

This project presents a **Passive Open-Source Intelligence (OSINT) Assessment** conducted against **NIIT Port Harcourt** to identify publicly available information relating to the organization's digital footprint. The assessment evaluates digital exposure, infrastructure visibility, human attack surface, and intelligence correlation using non-intrusive OSINT techniques to identify potential security risks before a breach occurs.

---

## 📄 Executive Summary

This assessment evaluated the publicly accessible digital footprint of **NIIT Port Harcourt** using passive Open-Source Intelligence (OSINT) techniques. The investigation identified publicly exposed organizational information, internet-facing infrastructure, and human attack surface indicators that could be leveraged by a threat actor during the reconnaissance phase of an attack. The findings demonstrate how publicly available information can be correlated to support phishing, social engineering, credential harvesting, and other pre-breach attack scenarios. The report concludes with prioritized security recommendations to help reduce the organization's overall exposure.

---

## 🎯 Objectives

- 🔍 Identify publicly available organizational information.
- 🌐 Assess digital exposure and online presence.
- 🖥️ Discover publicly accessible infrastructure and services.
- 👥 Analyze the organization's human attack surface.
- 📊 Correlate intelligence to identify realistic attack scenarios.
- 📄 Produce a professional Enterprise Threat Intelligence Report.

---

## 🛠️ Methodology

```text
Planning
    │
    ▼
Exposure Identification
    │
    ▼
Infrastructure Accessibility
    │
    ▼
Human Attack Surface Analysis
    │
    ▼
Intelligence Correlation
    │
    ▼
Risk Assessment
    │
    ▼
Security Recommendations
```

---

## ⚙️ Tools Used

| Tool | Purpose |
|------|---------|
| 🌐 Google Dorking | Information Discovery |
| 🕸️ Maltego | Relationship Mapping |
| 🌍 Domain Dossier | Domain & Infrastructure Enumeration |
| 📡 Nmap | Host & Service Enumeration |

---

## 🔍 Key Findings

- Employee identities and email addresses were publicly exposed.
- Publicly accessible login portal operating over HTTP.
- Email infrastructure and subdomains were discoverable.
- DNSSEC was not enabled on the target domain.
- Public organizational information increased the risk of phishing and social engineering.
- Intelligence correlation demonstrated realistic credential harvesting and Business Email Compromise (BEC) attack scenarios.

---

## 🛡️ Security Recommendations

- ✅ Enable HTTPS/SSL across all web services.
- ✅ Configure DMARC, SPF, and DKIM.
- ✅ Enforce Multi-Factor Authentication (MFA).
- ✅ Conduct regular phishing and security awareness training.
- ✅ Implement DNSSEC.
- ✅ Reduce unnecessary public information exposure.
- ✅ Monitor login attempts and suspicious authentication activity.
- ✅ Perform periodic OSINT assessments.

---

## 🎯 MITRE ATT&CK Mapping

| MITRE ATT&CK Tactic | Technique |
|---------------------|-----------|
| Reconnaissance | Gather Victim Identity Information (T1589) |
| Reconnaissance | Gather Victim Organization Information (T1591) |
| Reconnaissance | Gather Victim Network Information (T1590) |
| Initial Access | Phishing (T1566) |
| Initial Access | Valid Accounts (T1078) |
| Credential Access | Brute Force (T1110) |

---

## ⚠️ Disclaimer

This project was conducted **solely for educational and cybersecurity learning purposes**. All information presented in this assessment was obtained through **passive Open-Source Intelligence (OSINT)** techniques using publicly available sources. No unauthorized access, exploitation, or intrusion into the target organization's systems was performed. This project is intended to demonstrate threat intelligence methodologies and promote responsible cybersecurity practices.

---
## Author
Chigbo Valentine
