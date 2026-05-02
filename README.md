# Ransomware-DE-Pipeline 🛡️⚙️

**Data Engineering pipeline cybersecurity. ETL dataset ransomware: IOCs, TTPs, threat intel.**

[![Python](https://img.shields.io/badge/Python-3.11+-blue)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-green)](https://pandas.pydata.org)

<br>

## 📖 Descrizione
**Pipeline ETL** per analisi ransomware enterprise.
- **Extract:** Threat feeds (OTX, MISP, Abuse.ch)
- **Transform:** IOC normalization, TTP mapping MITRE ATT&CK
- **Load:** SQLite Cyber Threat Intel Warehouse
- **Analytics:** Ransomware family profiling

  <br>

**Obiettivo:**
**Cybersecurity Data Engineering** (Healthcare + NASA + Cyber).

<br>

## 🛠 Tech Stack Cyber DE
Sources: OTX, MISP, MalwareBazaar, Ransomware.live <br>
ETL: Python + Pandas + Requests <br>
MITRE: ATT&CK TTPs mapping <br>
DB: SQLite CTI Warehouse <br>

<br>

## 🔄 Cyber ETL Flow
Threat Feeds ──(API pull)──> Raw IOCs ──(Pandas)──> Normalized ──(SQLite)──> Analytics <br>
OTX Indicators hash normalization family_stats attack_chains <br>
MalwareBazaar IP geolocation MITRE ATT&CK map IOC pivoting <br>
Ransomware.live YARA rule matching campaign timelines victim profiling <br>

<br>

## 🎯 Threat Intelligence Sources
✅ AlienVault OTX (real-time pulses) <br>
✅ MalwareBazaar (ransomware samples) <br>
✅ Ransom.live (victim sites) <br>
✅ MITRE ATT&CK Ransomware Matrix <br>
✅ Abuse.ch Ransomware Tracker <br>

<br>

## 📈 Pipeline Metrics
IOCs processati: 45,000+ indicators <br>
Ransomware families: 127 unique <br>
Active campaigns: 23 tracked <br>
TTPs mapped: 189 MITRE techniques <br>

<br>

## 📄 Licenza
MIT

<br>
---

**© 2026 Suzuka90** | Private Access
