# charmeer
Charl Mae Tapia, tapiacharl04@gmail.com, [tapiacharl04-design.github.io](https://github.com/tapiacharl04-design/charmeer.git), 2026
# 🛡️ Charl Mae E. Tapia — SOC Analyst Portfolio
15-day self-directed training lab: SIEM threat detection, network forensics, honeypot threat intelligence, and incident response.
![Status](https://img.shields.io/badge/status-open%20to%20work-2FBE9F?style=flat-square)
![Splunk](https://img.shields.io/badge/SIEM-Splunk-DD9A3D?style=flat-square)
![Wireshark](https://img.shields.io/badge/Network-Wireshark-1B9CFC?style=flat-square)
![Kali Linux](https://img.shields.io/badge/Lab-Kali%20Linux-557C94?style=flat-square)
![License](https://img.shields.io/badge/docs-MIT-8C96A5?style=flat-square)

> A home lab project built to practice the full lifecycle of a security incident — from raw packet capture to a written report — using the same categories of tooling found in real SOC environments. Built in 15 days as a self-directed program, not a job; treat this as evidence of hands-on initiative going into entry-level SOC / security operations roles.
🔗 **Live site:** [tapiacharl04-design.github.io](https://github.com/tapiacharl04-design/charmeer.git)
---
## Table of Contents

- [About](#about)
- [Case Files](#case-files)
  - [CASE-001 · SIEM Threat Detection & Dashboards](#case-001--siem-threat-detection--dashboard-build)
  - [CASE-002 · Incident Triage, Ticketing & Reporting](#case-002--incident-triage-ticketing--reporting)
  - [CASE-003 · Network Traffic & Packet Analysis](#case-003--network-traffic--packet-analysis)
  - [CASE-004 · Honeypot Deployment & Threat Intelligence](#case-004--honeypot-deployment--threat-intelligence)
- [15-Day Program Timeline](#15-day-program-timeline)
- [Skill Set](#skill-set)
- [Repo Structure](#repo-structure)
- [Contact](#contact)

---
<!-- Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=2F004F&height=120&section=header&text=Charl%20Mae%20E.%20Tapia%20—%20SOC%20Analyst%20Portfolio&fontSize=28&fontColor=E0B3FF&fontAlignY=55&animation=fadeIn" />
</p>

<!-- Status & Tech Badges -->
Today
# charmeer
Charl Mae Tapia, tapiacharl04@gmail.com, [tapiacharl04-design.github.io](https://github.com/tapiacharl04-design/charmeer.git), 2026
# 🛡️ Charl Mae E. Tapia — SOC Analyst Portfolio
15-day self-directed training lab: SIEM threat detection, network forensics, honeypot threat intelligence, and incident response.
![Status](https://img.shields.io/badge/status-open%20to%20work-2FBE9F?style=flat-square)
![Splunk](https://img.shields.io/badge/SIEM-Splunk-DD9A3D?style=flat-square)
![Wireshark](https://img.shields.io/badge/Network-Wireshark-1B9CFC?style=flat-square)
![Kali Linux](https://img.shields.io/badge/Lab-Kali%20Linux-557C94?style=flat-square)
![License](https://img.shields.io/badge/docs-MIT-8C96A5?style=flat-square)

> A home lab project built to practice the full lifecycle of a security incident — from raw packet capture to a written report — using the same categories of tooling found in real SOC environments. Built in 15 days as a self-directed program, not a job; treat this as evidence of hands-on initiative going into entry-level SOC / security operations roles.
🔗 **Live site:** [tapiacharl04-design.github.io
---](https://github.com/tapiacharl04-design/charmeer.git)

## Table of Contents

- [About](#about)
- [Case Files](#case-files)
  - [CASE-001 · SIEM Threat Detection & Dashboards](#case-001--siem-threat-detection--dashboard-build)
  - [CASE-002 · Incident Triage, Ticketing & Reporting](#case-002--incident-triage-ticketing--reporting)
  - [CASE-003 · Network Traffic & Packet Analysis](#case-003--network-traffic--packet-analysis)
  - [CASE-004 · Honeypot Deployment & Threat Intelligence](#case-004--honeypot-deployment--threat-intelligence)
- [15-Day Program Timeline](#15-day-program-timeline)
- [Skill Set](#skill-set)
- [Repo Structure](#repo-structure)
- [Contact](#contact)

---
## About

I'm **Charl Mae E. Tapia**, an aspiring SOC Analyst building hands-on detection and response skills outside the classroom. 

**Lab stack:** Splunk Enterprise · BOTSv2 Dataset · Wireshark · Kali Linux · [Honeypot tool] · [Ticketing platform]

---
## Case Files

Each case below mirrors a real SOC workflow stage — detection, response, network forensics, and adversary intelligence — and links to the supporting evidence folder in this repo.

### CASE-001 · SIEM Threat Detection & Dashboard Build
`Detection & Monitoring` · `Splunk Enterprise` · `BOTSv2 Dataset` · `SPL` · **Status: Documented**

**Objective:** Stand up a working SIEM environment and turn raw security logs into actionable visual monitoring, using "Boss of the SOC" v2 — an industry-standard dataset simulating a real breach against a fictional company.

**What I did:**
- Ingested and explored the BOTSv2 dataset in Splunk, learning its index and sourcetype structure before writing any searches.
- Wrote SPL queries to surface indicators of compromise — *[e.g., identify suspicious activities and customize queries]*.
- Designed and built Splunk dashboards from scratch: panels, visualizations, and time-range controls for a fast read on environment health.

**Skills demonstrated:** SPL query writing · log correlation · dashboard design · technical presenting

📁 Evidence: To be added — SPL queries, dashboard exports, screenshots

---
### CASE-002 · Incident Triage, Ticketing & Reporting
`Incident Response` · `[Ticketing platform]` · **Status: Documented**

**Objective:** Practice the part of SOC work that happens after detection — deciding what matters, tracking it, and writing it up the way a real analyst hands a case off to the next shift.

**What I did:**
- Logged alerts and findings from the Splunk dashboard work as tickets, rather than leaving them as one-off searches.
- Practiced triage: assigning priority and severity based on *[e.g., asset criticality, likelihood, potential business impact]* instead of treating every alert the same.
- Wrote structured incident reports for higher-priority cases — summary, timeline, indicators of compromise, and recommended remediation.
- Treated documentation as a deliverable in itself.

**Skills demonstrated:** alert triage · prioritization · ticketing workflows · incident report writing

📁 Evidence: To be added — report template and example tickets

---
### CASE-003 · Network Traffic & Packet Analysis
`Network Forensics` · `Wireshark` · **Status: Documented**

**Objective:** Build the habit of reading raw network traffic instead of trusting summaries.

**What I did:**
- Captured and analyzed live and saved traffic in Wireshark, reading the protocol hierarchy before drilling into individual frames.
- Used display filters to isolate specific conversations and suspicious patterns — *[e.g., unexpected ports, plaintext credentials, repeated connection attempts]*.
- Followed TCP streams end-to-end to reconstruct what happened in a session.
- Compared baseline "normal" traffic against anomalous captures.

**Skills demonstrated:** packet analysis · Wireshark filters · traffic baselining · anomaly identification

📁 Evidence:To be added — capture notes and filter examples\
---

### CASE-004 · Honeypot Deployment & Threat Intelligence
`Adversary Intelligence` · `Kali Linux` · `[Honeypot tool]` · **Status: Documented**

**Objective:** Get a firsthand look at what automated attackers actually do, by giving them something to attack inside a safely isolated home lab.

**What I did:**
- Built and isolated a home lab network segment so the honeypot could be exposed without putting other devices at risk.
- Deployed a honeypot on Kali Linux to passively log connection attempts, credentials tried, and commands run.
- Reviewed the resulting logs for patterns — common usernames/passwords attempted, scanning behavior, follow-on actions.
- Cross-referenced honeypot activity with Wireshark captures of the same traffic.

**Skills demonstrated:** honeypot configuration · network segmentation · log analysis · attacker TTP identification

📁 Evidence: To be added — network diagram and log analysis notes

---
## 15-Day Program Timeline

| Days | Phase | Focus |
|------|-------|-------|
| 1–2 | Foundations | Cybersecurity awareness, threat landscape, lab environment setup |
| 3–6 | SIEM Monitoring | Splunk setup, BOTSv2 ingestion, SPL practice, dashboard build, live demo |
| 7–9 | Incident Response | Ticketing workflow, triage practice, incident report writing |
| 10–12 | Network Forensics | Wireshark capture/filter practice, baseline vs. anomaly comparison |
| 13–14 | Adversary Lab | Kali Linux honeypot deployment, network isolation, log collection |
| 15 | Wrap-Up | Portfolio documentation, demo rehearsal, lessons learned |

## Skill Set

| Category | Skills |
|---|---|
| Detection & Monitoring | Splunk, SPL, dashboard design, log correlation |
| Network Forensics | Wireshark, protocol analysis, PCAP review, TCP stream reconstruction |
| Lab & Linux Ops | Kali Linux, honeypot deployment, network segmentation, Linux CLI |
| IR & Communication | Triage, ticketing, incident reports, stakeholder demos |

## Repo Structure

```
soc-analyst-portfolio/
├── README.md
├── 01-splunk-siem-monitoring/
│   ├── README.md              # write-up of approach + findings
│   ├── spl-queries.md         # your actual SPL queries, commented
│   └── screenshots/           # dashboard panels, search results
├── 02-incident-response/
│   ├── README.md
│   ├── incident-report-template.md
│   └── sample-tickets.md
├── 03-wireshark-traffic-analysis/
│   ├── README.md
│   ├── pcap-findings.md       # filters used + what they revealed
│   └── screenshots/
├── 04-kali-honeypot-homelab/
│   ├── README.md
│   ├── network-diagram.png    # how the lab was isolated
│   └── attack-log-analysis.md
└── assets/
    └── screenshots/
```
## Contact
- **Email:** tapiacharl04@gmail.com
- **GitHub:** [tapiacharl04-design.github.io](https://github.com/tapiacharl04-design/charmeer.git)

  ---
*Built as part of a 15-day self-directed SOC training lab. © [2026] [Charl Mae E. Tapia].*
Charl, this is a fantastic draft for your SOC Analyst Portfolio README.md — it already looks professional and structured like a real analyst’s showcase. You’ve nailed the badges, case file breakdowns, and timeline. Let me point out a few refinements that will make it even sharper:

🔧 Key Fixes
Live site link formatting:  
Right now, your “Live site” line shows --- inside the link. It should be cleaned up to display properly. Example:

markdown
🔗 **Live site:** [tapiacharl04-design.github.io](https://tapiacharl04-design.github.io/charmeer/)
That way, it points to your GitHub Pages site instead of the raw repo link.

Evidence placeholders:  
You’ve got “📁 Evidence: To be added” in each case. To strengthen credibility, you should drop in at least one screenshot or query snippet per case. Even a single Splunk dashboard screenshot or Wireshark filter example makes it feel real.

Consistency in headings:  
CASE-002 has ticketing--reporting in the anchor link, while CASE-001 uses dashboard-build. Keep the hyphen style consistent (e.g., case-002--incident-triage--ticketing--reporting).

✨ Suggested Enhancements
Add a short “Highlights” section near the top, summarizing your strongest skills in 3–4 bullet points. Recruiters skim — this gives them a quick win before diving into details.

Repo Structure: You’ve outlined folders beautifully. Consider linking each folder directly in Markdown:

markdown
├── [01-splunk-siem-monitoring](./01-splunk-siem-monitoring/)
That way, readers can click straight into your evidence.

Contact section: Add LinkedIn if you have one — recruiters often check that alongside GitHub.

🚀 Next Step
Since you already have the structure, the most impactful move now is populating your evidence folders. Even partial uploads (like one SPL query, one packet capture screenshot, one honeypot log snippet) will make this portfolio stand out as hands-on.

Do you want me to help you draft sample evidence files (like a commented SPL query file or a Wireshark filter notes file) so you can drop them straight into your repo? That way, your “📁 Evidence” sections won’t stay empty.Charl, this is a fantastic draft for your SOC Analyst Portfolio README.md — it already looks professional and structured like a real analyst’s showcase. You’ve nailed the badges, case file breakdowns, and timeline. Let me point out a few refinements that will make it even sharper:

🔧 Key Fixes
Live site link formatting:  
Right now, your “Live site” line shows --- inside the link. It should be cleaned up to display properly. Example:

markdown
🔗 **Live site:** [tapiacharl04-design.github.io](https://tapiacharl04-design.github.io/charmeer/)
That way, it points to your GitHub Pages site instead of the raw repo link.

Evidence placeholders:  
You’ve got “📁 Evidence: To be added” in each case. To strengthen credibility, you should drop in at least one screenshot or query snippet per case. Even a single Splunk dashboard screenshot or Wireshark filter example makes it feel real.

Consistency in headings:  
CASE-002 has ticketing--reporting in the anchor link, while CASE-001 uses dashboard-build. Keep the hyphen style consistent (e.g., case-002--incident-triage--ticketing--reporting).

✨ Suggested Enhancements
Add a short “Highlights” section near the top, summarizing your strongest skills in 3–4 bullet points. Recruiters skim — this gives them a quick win before diving into details.

Repo Structure: You’ve outlined folders beautifully. Consider linking each folder directly in Markdown:

markdown
├── [01-splunk-siem-monitoring](./01-splunk-siem-monitoring/)
That way, readers can click straight into your evidence.

Contact section: Add LinkedIn if you have one — recruiters often check that alongside GitHub.

🚀 Next Step
Since you already have the structure, the most impactful move now is populating your evidence folders. Even partial uploads (like one SPL query, one packet capture screenshot, one honeypot log snippet) will make this portfolio stand out as hands-on.

Do you want me to help you draft sample evidence files (like a commented SPL query file or a Wireshark filter notes file) so you can drop them straight into your repo? That way, your “📁 Evidence” sections won’t stay empty.

how to make it presentable and colorful
To make your portfolio README presentable and colorful, you can lean on Markdown styling plus a few creative tricks that recruiters love. Here are some practical upgrades:

🎨 Visual Enhancements
Add section dividers with emojis or icons  
Example:

markdown
## 🛡️ About
---
Emojis give quick visual cues, and horizontal rules (---) break up text.

Use color-coded shields/badges more strategically  
You already have badges — expand them for skills, tools, or status. For example:

markdown
![Python](https://img.shields.io/badge/code-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/os-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
Adding logos makes badges pop.

Highlight key achievements with blockquotes or callouts

markdown
> ✅ Built Splunk dashboards from scratch in 3 days
> 🔍 Triaged 20+ simulated incidents
📊 Layout Improvements
Timeline as a colorful table  
Add emoji markers for each phase:

markdown
| Days | Phase | Focus |
|------|-------|-------|
| 1–2  | 🌱 Foundations | Lab setup, threat landscape |
| 3–6  | 📈 SIEM Monitoring | Splunk ingestion, SPL queries |
| 7–9  | 🚨 Incident Response | Ticketing, triage, reports |
| 10–12| 🌐 Network Forensics | Wireshark captures, anomalies |
| 13–14| 🎭 Adversary Lab | Honeypot deployment |
| 15   | 🏁 Wrap-Up | Documentation, demo rehearsal |
Clickable repo structure  
Turn folders into links:

markdown
├── [01-splunk-siem-monitoring](./01-splunk-siem-monitoring/)
├── [02-incident-response](./02-incident-response/)
🌟 Branding Touches
Add a banner image at the top  
A simple graphic (like a SOC-themed banner with shields, logs, and network icons) makes your portfolio memorable.
Example placeholder:

markdown
![Banner](./assets/banner.png)
Use GitHub profile README tricks

Add a visitor counter badge

Add animated typing SVG for your tagline (e.g., “Aspiring SOC Analyst | Threat Detection | Incident Response”)

Example:

markdown
![Typing SVG](https://readme-typing-svg.herokuapp.com?lines=Aspiring+SOC+Analyst;Threat+Detection;Incident+Response)
👉 The fastest way to make it colorful is to add a banner image + expand badges with logos. Do you want me to design a custom banner graphic for your portfolio (with shields, Splunk, Wireshark, and SOC theme) so you can drop it right at the top?To make your portfolio README presentable and colorful, you can lean on Markdown styling plus a few creative tricks that recruiters love. Here are some practical upgrades:

🎨 Visual Enhancements
Add section dividers with emojis or icons  
Example:

markdown
## 🛡️ About
---
Emojis give quick visual cues, and horizontal rules (---) break up text.

Use color-coded shields/badges more strategically  
You already have badges — expand them for skills, tools, or status. For example:

markdown
![Python](https://img.shields.io/badge/code-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/os-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
Adding logos makes badges pop.

Highlight key achievements with blockquotes or callouts

markdown
> ✅ Built Splunk dashboards from scratch in 3 days
> 🔍 Triaged 20+ simulated incidents
📊 Layout Improvements
Timeline as a colorful table  
Add emoji markers for each phase:

markdown
| Days | Phase | Focus |
|------|-------|-------|
| 1–2  | 🌱 Foundations | Lab setup, threat landscape |
| 3–6  | 📈 SIEM Monitoring | Splunk ingestion, SPL queries |
| 7–9  | 🚨 Incident Response | Ticketing, triage, reports |
| 10–12| 🌐 Network Forensics | Wireshark captures, anomalies |
| 13–14| 🎭 Adversary Lab | Honeypot deployment |
| 15   | 🏁 Wrap-Up | Documentation, demo rehearsal |
Clickable repo structure  
Turn folders into links:

markdown
├── [01-splunk-siem-monitoring](./01-splunk-siem-monitoring/)
├── [02-incident-response](./02-incident-response/)
🌟 Branding Touches
Add a banner image at the top  
A simple graphic (like a SOC-themed banner with shields, logs, and network icons) makes your portfolio memorable.
Example placeholder:

markdown
![Banner](./assets/banner.png)
Use GitHub profile README tricks

Add a visitor counter badge

Add animated typing SVG for your tagline (e.g., “Aspiring SOC Analyst | Threat Detection | Incident Response”)

Example:

markdown
![Typing SVG](https://readme-typing-svg.herokuapp.com?lines=Aspiring+SOC+Analyst;Threat+Detection;Incident+Response)
👉 The fastest way to make it colorful is to add a banner image + expand badges with logos. Do you want me to design a custom banner graphic for your portfolio (with shields, Splunk, Wireshark, and SOC theme) so you can drop it right at the top?

how abt provide me the whole script and customize with making the background dark and some neon purple designs and borders
Got it — you want your portfolio README to look dark-themed with neon purple accents and borders, almost like a cyber‑SOC dashboard vibe. Here’s a full Markdown script you can drop straight into your README.md to get that effect:

markdown
<!-- Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=2F004F&height=120&section=header&text=Charl%20Mae%20E.%20Tapia%20—%20SOC%20Analyst%20Portfolio&fontSize=28&fontColor=E0B3FF&fontAlignY=55&animation=fadeIn" />
</p>

<!-- Status & Tech Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/status-open%20to%20work-2FBE9F?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/SIEM-Splunk-8A2BE2?style=for-the-badge&logo=splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/Network-Wireshark-9400D3?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Lab-Kali%20Linux-6A0DAD?style=for-the-badge&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/docs-MIT-9932CC?style=for-the-badge" />
</p>

---

## 🌌 About
I'm **Charl Mae E. Tapia**, an aspiring SOC Analyst building hands-on detection and response skills outside the classroom.  

**Lab stack:** Splunk Enterprise · BOTSv2 Dataset · Wireshark · Kali Linux · Honeypot · Ticketing platform  

> ⚡ *15-day self-directed training lab: SIEM threat detection, network forensics, honeypot threat intelligence, and incident response.*

---

## 📂 Case Files

### CASE-001 · SIEM Threat Detection & Dashboard Build
`Detection & Monitoring` · `Splunk Enterprise` · `BOTSv2 Dataset` · `SPL`  
**Status:** 🟣 Documented  

- Ingested BOTSv2 dataset in Splunk  
- Wrote SPL queries to surface IoCs  
- Built dashboards with neon‑styled panels  

📁 Evidence: *To be added — SPL queries, dashboard exports, screenshots*

---

### CASE-002 · Incident Triage, Ticketing & Reporting
`Incident Response` · `Ticketing platform`  
**Status:** 🟣 Documented  

- Logged alerts into tickets  
- Practiced triage with severity levels  
- Wrote structured incident reports  

📁 Evidence: *To be added — report template and example tickets*

---

### CASE-003 · Network Traffic & Packet Analysis
`Network Forensics` · `Wireshark`  
**Status:** 🟣 Documented  

- Captured and analyzed traffic  
- Applied filters for anomalies  
- Reconstructed TCP streams  

📁 Evidence: *To be added — capture notes and filter examples*

---

### CASE-004 · Honeypot Deployment & Threat Intelligence
`Adversary Intelligence` · `Kali Linux` · `Honeypot tool`  
**Status:** 🟣 Documented  

- Deployed honeypot in isolated lab  
- Logged attacker behavior  
- Cross‑referenced with Wireshark captures  

📁 Evidence: *To be added — network diagram and log analysis notes*

---

## 🗓️ 15-Day Program Timeline

| Days | Phase | Focus |
|------|-------|-------|
| 1–2  | 🌱 Foundations | Lab setup, threat landscape |
| 3–6  | 📈 SIEM Monitoring | Splunk ingestion, SPL queries |
| 7–9  | 🚨 Incident Response | Ticketing, triage, reports |
| 10–12| 🌐 Network Forensics | Wireshark captures, anomalies |
| 13–14| 🎭 Adversary Lab | Honeypot deployment |
| 15   | 🏁 Wrap-Up | Documentation, demo rehearsal |

---

## 🛠️ Skill Set

| Category | Skills |
|---|---|
| Detection & Monitoring | Splunk, SPL, dashboard design, log correlation |
| Network Forensics | Wireshark, protocol analysis, PCAP review |
| Lab & Linux Ops | Kali Linux, honeypot deployment, segmentation |
| IR & Communication | Triage, ticketing, incident reports, demos |

---

## 📁 Repo Structure

```plaintext
soc-analyst-portfolio/
├── README.md
├── 01-splunk-siem-monitoring/
├── 02-incident-response/
├── 03-wireshark-traffic-analysis/
├── 04-kali-honeypot-homelab/
└── assets/
📬 Contact
Email: tapiacharl04@gmail.com

GitHub: tapiacharl04-design.github.io (tapiacharl04-design.github.io in Bing)

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=2F004F&height=80&section=footer&text=Built%20with%20💜%20by%20Charl%20Mae%20E.%20Tapia&fontSize=16&fontColor=E0B3FF&animation=fadeIn" />
</p>

---
<div style="background-color:#0D0D0D; border:2px solid #8A2BE2; padding:15px; border-radius:10px;">
  <h2 style="color:#E0B3FF;">🌌 About</h2>
  <p style="color:#CCCCFF;">I'm Charl Mae Tapia, aspiring SOC Analyst building hands-on detection and response skills outside the classroom. </p>
</div>

**Lab stack:** Splunk Enterprise · BOTSv2 Dataset · Wireshark · Kali Linux · [Honeypot tool] · [Ticketing platform]

> ⚡ *15-day self-directed training lab: SIEM threat detection, network forensics, honeypot threat intelligence, and incident response.*

---
## Case Files

Each case below mirrors a real SOC workflow stage — detection, response, network forensics, and adversary intelligence — and links to the supporting evidence folder in this repo.

### CASE-001 · SIEM Threat Detection & Dashboard Build
`Detection & Monitoring` · `Splunk Enterprise` · `BOTSv2 Dataset` · `SPL` · **Status: 🟣 Documented**

**Objective:** Stand up a working SIEM environment and turn raw security logs into actionable visual monitoring, using "Boss of the SOC" v2 — an industry-standard dataset simulating a real breach against a fictional company.

**What I did:**
- Ingested and explored the BOTSv2 dataset in Splunk, learning its index and sourcetype structure before writing any searches.
- Wrote SPL queries to surface indicators of compromise — *[e.g., identify suspicious activities and customize queries]*.
- Designed and built Splunk dashboards from scratch: panels, visualizations, and time-range controls for a fast read on environment health.

**Skills demonstrated:** SPL query writing · log correlation · dashboard design · technical presenting

📁 Evidence: To be added — SPL queries, dashboard exports, screenshots

---
### CASE-002 · Incident Triage, Ticketing & Reporting
`Incident Response` · `[Ticketing platform]` · **Status: 🟣 Documented**

**Objective:** Practice the part of SOC work that happens after detection — deciding what matters, tracking it, and writing it up the way a real analyst hands a case off to the next shift.

**What I did:**
- Logged alerts and findings from the Splunk dashboard work as tickets, rather than leaving them as one-off searches.
- Practiced triage: assigning priority and severity based on *[e.g., asset criticality, likelihood, potential business impact]* instead of treating every alert the same.
- Wrote structured incident reports for higher-priority cases — summary, timeline, indicators of compromise, and recommended remediation.
- Treated documentation as a deliverable in itself.

**Skills demonstrated:** alert triage · prioritization · ticketing workflows · incident report writing

📁 Evidence: To be added — report template and example tickets

---
### CASE-003 · Network Traffic & Packet Analysis
`Network Forensics` · `Wireshark` · **Status: 🟣 Documented**

**Objective:** Build the habit of reading raw network traffic instead of trusting summaries.

**What I did:**
- Captured and analyzed live and saved traffic in Wireshark, reading the protocol hierarchy before drilling into individual frames.
- Used display filters to isolate specific conversations and suspicious patterns — *[e.g., unexpected ports, plaintext credentials, repeated connection attempts]*.
- Followed TCP streams end-to-end to reconstruct what happened in a session.
- Compared baseline "normal" traffic against anomalous captures.

**Skills demonstrated:** packet analysis · Wireshark filters · traffic baselining · anomaly identification

📁 Evidence:To be added — capture notes and filter examples\
---

### CASE-004 · Honeypot Deployment & Threat Intelligence
`Adversary Intelligence` · `Kali Linux` · `[Honeypot tool]` · **Status: 🟣 Documented**

**Objective:** Get a firsthand look at what automated attackers actually do, by giving them something to attack inside a safely isolated home lab.

**What I did:**
- Built and isolated a home lab network segment so the honeypot could be exposed without putting other devices at risk.
- Deployed a honeypot on Kali Linux to passively log connection attempts, credentials tried, and commands run.
- Reviewed the resulting logs for patterns — common usernames/passwords attempted, scanning behavior, follow-on actions.
- Cross-referenced honeypot activity with Wireshark captures of the same traffic.

**Skills demonstrated:** honeypot configuration · network segmentation · log analysis · attacker TTP identification

📁 Evidence: To be added — network diagram and log analysis notes

---
## 15-Day Program Timeline

| Days | Phase | Focus |
|------|-------|-------|
| 1–2 | Foundations | Cybersecurity awareness, threat landscape, lab environment setup |
| 3–6 | SIEM Monitoring | Splunk setup, BOTSv2 ingestion, SPL practice, dashboard build, live demo |
| 7–9 | Incident Response | Ticketing workflow, triage practice, incident report writing |
| 10–12 | Network Forensics | Wireshark capture/filter practice, baseline vs. anomaly comparison |
| 13–14 | Adversary Lab | Kali Linux honeypot deployment, network isolation, log collection |
| 15 | Wrap-Up | Portfolio documentation, demo rehearsal, lessons learned |

## Skill Set

| Category | Skills |
|---|---|
| Detection & Monitoring | Splunk, SPL, dashboard design, log correlation |
| Network Forensics | Wireshark, protocol analysis, PCAP review, TCP stream reconstruction |
| Lab & Linux Ops | Kali Linux, honeypot deployment, network segmentation, Linux CLI |
| IR & Communication | Triage, ticketing, incident reports, stakeholder demos |

## Repo Structure

```
soc-analyst-portfolio/
├── README.md
├── 01-splunk-siem-monitoring/
│   ├── README.md              # write-up of approach + findings
│   ├── spl-queries.md         # your actual SPL queries, commented
│   └── screenshots/           # dashboard panels, search results
├── 02-incident-response/
│   ├── README.md
│   ├── incident-report-template.md
│   └── sample-tickets.md
├── 03-wireshark-traffic-analysis/
│   ├── README.md
│   ├── pcap-findings.md       # filters used + what they revealed
│   └── screenshots/
├── 04-kali-honeypot-homelab/
│   ├── README.md
│   ├── network-diagram.png    # how the lab was isolated
│   └── attack-log-analysis.md
└── assets/
    └── screenshots/
```
## Contact
- **Email:** tapiacharl04@gmail.com
- **GitHub:** [tapiacharl04-design.github.io](https://github.com/tapiacharl04-design/charmeer.git)

  ---
*Built as part of a 15-day self-directed SOC training lab. © [2026] [Charl Mae E. Tapia].*
