# Surface Labs — SDR Toolkit

Two self-contained tools built for the Surface Labs founding sales team. Zero dependencies, no backend, deploys to Vercel in one click.

---

## Tools

### 1. SDR Command Center — `/`
Tracks outcomes and revenue progress against the $800K ARR goal.

- Revenue progress bar — live tracking across 120-day window with sprint markers
- Conversion funnel — Outreach → Response → Meeting → Demo → Proposal → Closed Won
- Pipeline stage breakdown — dollar values by deal stage
- Activity log — full history with company, contact, type, value, source, date, notes
- 8-week rolling bar chart — activity volume by week
- KPI health check — reply rate, meeting rate, demo rate, close rate, avg deal size

### 2. Outreach Tracker — `/outreach-tracker`
Contact-level follow-up tracker for the 50-contact campaign.

- Today's Actions panel — tells you exactly who to contact right now
- Urgency-sorted by default — overdue contacts surface automatically
- Days idle counter — auto-calculates from last contact date
- Follow-up counter — tracks 1st / 2nd / 3rd message per contact
- Kanban + table views — toggle between board and list
- CSV export — one-click dump for sharing with the team

---

## Deploy to Vercel

1. Create a new GitHub repo
2. Upload all 4 files: `index.html`, `outreach-tracker.html`, `vercel.json`, `README.md`
3. Go to [vercel.com](https://vercel.com) → New Project → Import repo
4. Framework: **Other** — hit Deploy
5. Live in ~30 seconds

**URLs after deploy:**
- `yoursite.vercel.app/` → SDR Command Center
- `yoursite.vercel.app/outreach-tracker` → Outreach Tracker

## Local Use

Open either `.html` file directly in any browser. No build step needed.

## Tech Stack

- Vanilla HTML/CSS/JS — zero dependencies
- Google Fonts (Syne, JetBrains Mono, DM Mono, Familjen Grotesk)
- localStorage for persistence — data lives in the browser
