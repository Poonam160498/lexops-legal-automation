# ⚖️ LexOps — Legal Operations Suite

**A working demo of four automation tools that give every law-firm associate back 6+ hours a week.**

Built by **[Your Name]** — Business Analyst with legal domain knowledge and technical skills.

> Dashboards show you the problem. Automation removes it. LexOps does both.

## 🔴 Live demo

Open `lexops-suite.html` in any browser — no installation, no dependencies, no build step.
(Or enable GitHub Pages on this repo and link it here.)

## The problem

Indian law firms run world-class legal work on operational workflows held together by memory, diaries and WhatsApp:

| Daily reality | Cost |
|---|---|
| A clerk manually scans 3–4 court cause lists every morning | ~45 min/day, and one missed listing = an unrepresented matter |
| Limitation dates tracked in a senior's head and a physical diary | One missed date = malpractice exposure |
| Clients call repeatedly after every hearing for status | 1–2 associate-hours lost daily |
| Juniors log "work done — 4 hrs"; partners rewrite invoices at night | Rejected invoices, delayed collections |

## The tools

###  Operations Dashboard
Firm-wide view: matter pipeline with days-in-stage, billable-hours split per fee earner, deadline tracker with urgency chips, practice-area mix, and a live "time recovered" ROI table.

### 📋 Cause List Monitor
Simulated 7 AM scan across Delhi HC, NCLT Mumbai and a district court — matches listings against the firm's matter index and drafts the morning team alert automatically.

### ⏳ Limitation Calculator
Select a filing type (Written Statement, First Appeal, SLP, Sec. 34 arbitration challenge, NCLAT/IBC appeal, NI Act 138 chain, consumer complaint), enter the trigger date, and get the full deadline chain with live countdowns and one-click calendar export.

### 💬 Client Update Bot
Pick the matter, the hearing outcome and the register (formal / warm) — a client-ready post-hearing update is drafted for one-click review and send.

### 🧾 Billing Narrative Cleaner
Paste raw time entries ("call with client abt reply — 0.5") and get client-ready narratives ("Telephone conference with client regarding reply/written submissions (0.5 hrs)").

## Why this needs legal + tech, not just tech

A generic developer doesn't know what a cause list is, how Sec. 34(3)'s condonation proviso works, or why "went thru opp side docs" gets an invoice rejected. A pure lawyer can't build the automation. **The value is the overlap.**

## Tech notes

- Single-file HTML/CSS/vanilla JS — zero dependencies, runs offline
- Demo data throughout; limitation periods are **indicative only** and clearly disclaimed in-app — production use requires litigation-team verification against the statute
- Production roadmap: eCourts/HC portal fetchers, case-management integration, WhatsApp Business API for client updates, LLM-drafted billing narratives with partner approval flow, audit trail

##  Disclaimer

This is a portfolio demonstration with dummy data. Nothing here is legal advice, and the limitation periods shown are simplified. Always verify deadlines against the Limitation Act, 1963 and the relevant statute before filing.

##  Contact

Open to legal-ops / business-analyst roles at law firms and legal-tech companies.

- LinkedIn: www.linkedin.com/in/poonam-nauroji
- Email: naurojipunam@gmail.com
