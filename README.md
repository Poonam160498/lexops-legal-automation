# ⚖️ LexOps — Legal Operations Suite

**A working demo of four automation tools that give every law-firm associate back 6+ hours a week.**

Built by **Poonam Nauroji** — Business Analyst with legal domain knowledge and technical skills.

> Dashboards show you the problem. Automation removes it. LexOps does both.

## 🔴 Live demo
https://poonam160498.github.io/lexops-legal-automation/ 
— no installation, no dependencies, no signup.

## 📸 Screenshots

### Operations Dashboard
Firm-wide view: matter pipeline with days-in-stage, billable-hours split, deadline urgency tracking, and a time-recovered ROI table.

![Operations Dashboard](screenshots/01-dashboard.png)

### 📋 Cause List Monitor
Simulated 7 AM scan across Delhi HC, NCLT Mumbai and a district court — matches listings against the firm's matter index and drafts the morning team alert automatically.

![Cause List Monitor](screenshots/02-cause-list.png)

### ⏳ Limitation Calculator
One trigger date in — the full deadline chain out, with live colour-coded countdowns (shown: Sec. 34 challenge to an arbitral award).

![Limitation Calculator](screenshots/03-limitation.png)

### 💬 Client Update Bot
Post-hearing client updates drafted in a formal or warm register — the associate reviews and sends in one click.

![Client Update Bot](screenshots/04-client-updates.png)

### 🧾 Billing Narrative Cleaner
"call with client abt reply — 0.5" becomes "Telephone conference with client regarding reply/written submissions (0.5 hrs)" — before/after, side by side.

![Billing Narrative Cleaner](screenshots/05-billing.png)

## The problem

Indian law firms run world-class legal work on operational workflows held together by memory, diaries and WhatsApp:

| Daily reality | Cost |
|---|---|
| A clerk manually scans 3–4 court cause lists every morning | ~45 min/day, and one missed listing = an unrepresented matter |
| Limitation dates tracked in a senior's head and a physical diary | One missed date = malpractice exposure |
| Clients call repeatedly after every hearing for status | 1–2 associate-hours lost daily |
| Juniors log "work done — 4 hrs"; partners rewrite invoices at night | Rejected invoices, delayed collections |

## Why this needs legal + tech, not just tech

A generic developer doesn't know what a cause list is, how Sec. 34(3)'s condonation proviso works, or why "went thru opp side docs" gets an invoice rejected. A pure lawyer can't build the automation. **The value is the overlap.**

## Tech notes

- Single-file HTML/CSS/vanilla JS — zero dependencies, runs offline
- Demo data throughout; limitation periods are **indicative only** and clearly disclaimed in-app — production use requires litigation-team verification against the statute
- Production roadmap: eCourts/HC portal fetchers, case-management integration, WhatsApp Business API for client updates, LLM-drafted billing narratives with partner approval flow, audit trail

## ⚠️ Disclaimer

This is a portfolio demonstration with dummy data. Nothing here is legal advice, and the limitation periods shown are simplified. Always verify deadlines against the Limitation Act, 1963 and the relevant statute before filing.

## 📬 Contact

Open to legal-ops / business-analyst roles at law firms and legal-tech companies.

- LinkedIn:www.linkedin.com/in/poonam-nauroji
- Email:naurojipunam@gmail.com
