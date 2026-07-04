<div align="center">

<h1>Siddharth Magdum</h1>

<p><strong>Security Engineer · Backend Engineer · AI Systems · Pune, India</strong></p>

<p>
Building production-grade endpoint security infrastructure and AI-assisted audit tooling.<br/>
I write systems that harden, audit, and protect infrastructure at scale.
</p>

<p>
  <a href="https://www.linkedin.com/in/siddharthmagdum/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://twitter.com/SiddharthM116">
    <img src="https://img.shields.io/badge/X%20%2F%20Twitter-000000?style=flat-square&logo=x&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://siddharth116-sudo.github.io/Portfolio/">
    <img src="https://img.shields.io/badge/Portfolio-111827?style=flat-square&logo=githubpages&logoColor=white"/>
  </a>
</p>

</div>

---

## What I'm Building

### HardSecNet-Enterprise

An endpoint hardening and compliance audit platform for Windows and Ubuntu fleets.

The platform runs a distributed agent model — lightweight Python agents deploy to endpoints, collect posture data, and report to a central Flask server. The server runs an AI-assisted risk engine, evaluates CIS Benchmark compliance, generates structured audit reports, and supports controlled remediation with rollback safety.

**Core system components:**

| Component | Role |
|---|---|
| `ai_engine.py` | AI-assisted vulnerability prioritisation and risk scoring |
| `cis_engine.py` | CIS Benchmark evaluation and compliance scoring |
| `linux_auditor.py` | Ubuntu/Debian endpoint audit engine |
| `Auditor.ps1` / `Hardener.ps1` | Windows CIS Benchmark enforcement via PowerShell |
| `ReportGenerator.py` | Structured HTML and JSON audit report generation |
| `pki_setup.py` | PKI infrastructure for agent-to-server mutual TLS |
| `middleware_auth.py` | RBAC-based API authentication |
| `app.py` | Central orchestration server — REST API, dashboard, state management |

**System architecture:**

```
Endpoint Agent (Python/PS)
      │
      ▼
Central Server (Flask · REST API · RBAC)
      │
      ├──► AI Risk Engine          (CVE correlation, risk scoring)
      ├──► CIS Compliance Engine   (benchmark evaluation, gap analysis)
      ├──► Report Generator        (HTML / JSON audit output)
      └──► Web Dashboard           (posture overview, remediation queue)
```

---

## Focus Areas

| Domain | What I work on |
|---|---|
| **Security Engineering** | CIS Benchmarks, endpoint hardening, OWASP Top 10, access control, path traversal |
| **AI Systems** | AI-assisted audit engines, risk scoring pipelines, AI-powered tooling |
| **Backend Engineering** | Python REST APIs, Flask, PowerShell orchestration, system automation |
| **Infrastructure** | Multi-platform agent deployment, PKI, RBAC, Docker |
| **Networking & Protocols** | TCP/IP internals, Wireshark, protocol analysis, network security |
| **Web Security** | OWASP Top 10, TryHackMe labs, broken access control, injection |

---

## Technical Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Infrastructure & Security**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Frameworks & Tools**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

## Currently

- Shipping `HardSecNet-Enterprise` — production endpoint security audit platform
- Studying web application security: path traversal, broken access control, injection
- Deep-diving TCP/IP stack and network security internals
- Selected for **TCS HackQuest Season 10** interview

---

## GitHub Activity

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=siddharth116-sudo&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=siddharth116-sudo&layout=compact&theme=github_dark&hide_border=true&langs_count=6)

![GitHub Streak](https://streak-stats.demolab.com/?user=siddharth116-sudo&theme=github-dark-blue&hide_border=true)

</div>

---

<div align="center">
  <sub>
    <a href="https://www.linkedin.com/in/siddharthmagdum/">LinkedIn</a> ·
    <a href="https://twitter.com/SiddharthM116">Twitter / X</a> ·
    <a href="https://siddharth116-sudo.github.io/Portfolio/">Portfolio</a>
  </sub>
</div>
