<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Inter&weight=800&size=32&pause=1000&color=A855F7&center=true&vCenter=true&width=600&height=60&lines=Hey%2C+I'm+Chhavi+%F0%9F%91%8B;AI%2FML+%2B+Full-Stack+Builder;GSSoC'26+Contributor" alt="Typing SVG" /></a>

### B.Tech CSE (AI & ML) @ VIT Bhopal · Building things that monitor, defend, and match people to opportunities

> *I like systems that watch themselves — dashboards that catch anomalies, tools that flag threats, agents that make decisions. Give me a stack and a real problem, and I'll ship something production-shaped.*

[![Profile views](https://komarev.com/ghpvc/?username=Chhavii2712&color=A855F7&style=for-the-badge)](https://github.com/Chhavii2712)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/chhavidubey)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dubeychhavi566@gmail.com)
[![GSSoC](https://img.shields.io/badge/GSSoC'26-Contributor-orange?style=for-the-badge)](https://github.com/Chhavii2712)

</div>

---

## What I do

- 🛰️ Build full-stack systems that turn raw signals into decisions — telemetry dashboards, threat scores, growth-stage clocks
- 🤖 Work across the ML pipeline: from scikit-learn scoring engines to agentic workflows and LLM-integrated apps
- 🔐 Getting increasingly into security — threat detection, MITRE ATT&CK mapping, autonomous mitigation logic
- 🌱 Currently exploring satellite imagery + ML for agricultural monitoring (Team ARC, BAH 2026 / ISRO)
- 📊 Learning ServiceNow ITSM & Agentic AI workflows alongside my core stack

---

## Why I build the way I do

Most student projects stop at "it works." I care about what happens after — does the dashboard actually surface the anomaly, does the mitigation logic fire before a human has to, does the model's threshold make sense on real data. That's the gap between a hackathon demo and something you'd trust in production, and it's the gap I keep trying to close.

---

## Current stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

**Frameworks & tools**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**AI / ML**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)

<details>
<summary><strong>Also on the radar</strong></summary>
<br/>

![ServiceNow](https://img.shields.io/badge/ServiceNow-ITSM_%7C_Flow_Designer-00A0DE?style=for-the-badge)
![Agentic AI](https://img.shields.io/badge/Agentic_AI-Workflows-8B5CF6?style=for-the-badge)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-Threat_Mapping-CC2936?style=for-the-badge)
![Satellite ML](https://img.shields.io/badge/Satellite_Imagery-Crop_%2F_Phenology_ML-16A34A?style=for-the-badge)

</details>

---

## Featured projects

### 🛰️ memvigo — real-time system health monitoring
Full-stack monitoring dashboard built with **Next.js 15**, Prisma, PostgreSQL, and Tailwind CSS. JWT-based auth, a paginated live alert feed, and a Java engine that POSTs telemetry every 30 seconds to simulate real-time ingestion. Currently extending it with Z-score anomaly detection and dynamic ML threshold lines on the dashboard charts.

**Live:** memvigo.vercel.app · **Source:** github.com/Chhavii2712/memvigo

`Next.js 15` · `Prisma` · `PostgreSQL` · `JWT` · `Tailwind CSS`

---

### 🛡️ ThreatShield — autonomous cyber threat response
Built at NEURO NEX'26 Hackathon with Team High-Five AI. Scores incoming threats (1–10 severity), classifies them into 11 threat types via a custom rule-based/ML engine, and auto-executes mitigation (block IP, kill process, isolate device) on HIGH/CRITICAL events — mapped to the MITRE ATT&CK framework.

Ships with a real-time SOC dashboard: live threat feed, severity donut charts, a geo-origin world map, an attack simulator (ransomware chain, data exfiltration, DDoS, brute force), and outbound webhooks to Slack, PagerDuty, and SIEM tools.

`React 19` · `Vite` · `MITRE ATT&CK` · `Threat Scoring Engine`

---

### 🌾 Crop & Irrigation Advisory — Team ARC (BAH 2026 / ISRO)
AI-driven system for crop type classification, moisture stress detection, and irrigation advisory from satellite imagery — with a phenology-anchored satellite-derived growth stage clock (PA-SGSC) as the core differentiator over standard classification approaches. Built with teammates Aashi and Rashi.

`Satellite Imagery` · `Applied ML` · `Agricultural Monitoring`

---

### 📋 student-attendance-tracker
A Java OOP application for tracking and reporting student attendance, built around clean data management and encapsulation principles.

`Java` · `OOP`

---

## Experience

- **GSSoC'26** — Contributor & Campus Ambassador (VIT Bhopal), resolving issues/feature requests in active open-source repos while driving student participation on campus
- **ServiceNow Virtual Internship (AICTE–SmartBridge)** — platform administration, ITSM fundamentals, Flow Designer, and Automated Test Framework, alongside CSA certification prep

---

## Beyond the code

- 🎤 Zonal Level Bronze Medalist, Debate (CICSE)
- 🌍 Delegate, MUN-Mate 2024 — diplomacy and global problem-solving
- 🎪 Core Member, iCreate Club VIT Bhopal (Event Management)
- 🏆 Hackathons: NEURO NEX'26, NextGen 2026, MATLAB Verse Nextwave, Visionary Hackathon

---

## GitHub stats

<div align="center">

![](https://github-readme-stats-woad-tau-37.vercel.app/api?username=Chhavii2712&theme=radical&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://streak-stats.demolab.com/?user=Chhavii2712&theme=radical&hide_border=false)<br/>
![](https://github-readme-stats-woad-tau-37.vercel.app/api/top-langs/?username=Chhavii2712&theme=radical&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

</div>

---

<div align="center">

*Open to internships, hackathon teams, and open-source collabs — especially anything at the intersection of ML and real-time systems.*

</div>
