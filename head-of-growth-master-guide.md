# LaWayra — Head of Growth: Master Guide

*The single reference for the Head of Growth role — what it is, who it oversees, everything it's responsible for running, and every SOP, dashboard, and link needed to run it.*

> **Transition:** Currently held by **Marcus**, transitioning to **Aliyah in August 2026.** Aliyah already runs the **Head of Sales** function, so the net-new surface for her is the **marketing / growth** side and the higher-level oversight that ties marketing and sales together.

---

## 1. What the Role Is

The **Head of Growth** owns the entire revenue engine — bringing prospects in (cold traffic), nurturing them (warm traffic), and converting them (sales) — and is accountable for the numbers at every step: **spend → leads → booked calls → shows → closes → paid retreats**, plus the attribution, reporting, and tech that measures all of it.

It sits above two halves that are usually treated as separate jobs:

- **Marketing** — paid ads, SEO, email, community, organic social, mar tech / dashboards.
- **Sales** — the closing team (reps, calendar management, show/close rates, rep commissions).

The role also coordinates a web of people (media buyers, sales reps, coaches, VAs, dev/SEO contractors) and keeps the leadership team informed via the weekly report.

---

## 2. Org Map — Who the Role Oversees

```
Head of Growth: Marcus → Aliyah (Aug 2026)
│
├── COLD TRAFFIC (new prospects)
│   ├── Google Ads media buyer ......... Andrew
│   ├── Facebook Ads media buyer ....... Andrew (+ Juan's own Book-a-Call campaign)
│   ├── SEO ............................ Gabor
│   ├── Reddit ......................... Aliyah / Jacobo
│   └── B2B prospecting ................ Kevin
│
├── SALES  (Head of Sales: Aliyah)
│   └── Reps: Aliyah, Jacobo, Nico, Thomas
│
├── WARM / NURTURE (organic)
│   ├── Community (Circle) ............. PM Aliyah · Leaders Aliyah/Monica/Ashley · Saul (tech) · Juli (admin)
│   ├── Integration / Coaching ........ PM Aliyah & Sarah · Coaches Aliyah/Monica/Ashley
│   ├── Email .......................... Marcus (→ Aliyah/Saul)
│   └── Organic Social / Content ...... Manager Sarah · Volunteer creators
│
├── MAR TECH
│   ├── Tech PM ........................ (open)
│   └── Tech team ..................... Saul / Jacobo (formerly Madhu)
│
└── CONTRACTORS
    ├── Web Developer .................. Fahad
    └── SEO ............................ Gabor
```

*(Sam owns his own projects — documentary, podcast, book, public speaking. Sarah is GM + volunteer onboarding/outreach. Those sit alongside, not under, Growth.)*

---

## 3. Responsibilities by Area

### A. Cold Traffic (Acquisition)
- **Google Ads** — the primary paid channel and most qualified lead source. Oversee media buyer (Andrew); watch spend / leads / CPL / bookings; protect the account from compliance rejections (a real risk for ayahuasca advertisers — the compliant site is a key competitive edge). 2025: ~$52.8K spend → ~$196.7K revenue, 3.72 ROAS.
- **Facebook / Meta Ads** — Andrew + Juan's own campaign. Own the Meta Pixel + CAPI events; keep Juan's private dashboard current.
- **SEO** — the single biggest cold channel (~50% of guests come from Google search). Gabor owns execution; the role owns the outcome. **Watch item:** SEO declined sharply through 2025 (peaked ~300 clicks/day in June, fell to ~100) — the main driver of the year's marketing dip.
- **Reddit** — a growing lead source, historically under-worked. Aliyah/Jacobo.
- **B2B prospecting** — Kevin.
- **Media-buyer attribution** — every lead attributed to the correct buyer by **lead-create date** (Marcus → Hafsa → Ida → Marcus → Andrew for Google; Juan/Marcus for Meta). Drives their commissions.

### B. Sales (Head of Sales function — Aliyah already owns this)
Pulled from the Head of Sales SOP, this is the closing side the Growth role is accountable for:
- **Track rep performance** — #1 responsibility: stay on top of **show rate** and **close rate** for every rep, at all times, so we hit monthly sales targets. Team benchmark: **30%+ live-call close rate, 50%+ show rate.**
- **Calendar management** — fill top reps first; new reps part-time; don't onboard new reps until the current roster's calendars are full.
- **Onboard / train reps** — set performance expectations upfront (volunteer, but ads cost money → profitability matters), capture availability + timezone, run ongoing trainings.
- **Rep support** — first point of contact for rep questions; escalate tech/GHL to the technologist, urgent deal-closing approvals to Sam.
- **Team management** — monthly team meeting + 1-on-1s.
- **Audit the AI SMS setter daily** — quick check that the AI SDR inbox isn't doing anything weird.
- Current reps: **Aliyah, Jacobo, Nico, Thomas.**

### C. Warm Traffic / Nurture
- **Community (Circle)** — systematize posting, virtual workshops, in-person events/chapters. Aliyah PM; Monica/Ashley leaders; Saul tech; Juli admin.
- **Integration / Coaching** — the free post-retreat integration-call funnel (Aliyah & Sarah PM; Aliyah/Monica/Ashley coach).
- **Email** — 40-email welcome sequence live (30–50% opens, ~1.5% clicks, ~98% deliverability). Roadmap: 180-day evergreen sequence, community/pre-retreat/post-retreat sequences, sales sequences (promos, abandoned-call, pre/post-call, post-purchase). Currently Marcus → transitioning to Aliyah/Saul.
- **Organic Social / Content** — 5-pillar Instagram strategy + the Content Machine production pipeline (carousels, Reels, cross-platform, Stories) with review-before-publish. Sarah manages; volunteers create. (Note: Meta banned old IG/FB group over ayahuasca compliance — organic social is more trust-signal than lead-gen.)

### D. Mar Tech, Attribution & Reporting
The technical backbone — arguably the most complex part of the role:
- **Three dashboards** — Sales Dashboard (per-call), Marketing/Ads Dashboard (per-day per-channel), Sales by Source (per-booking source attribution).
- **Vercel Dashboard** (`lw-sales-dashboard.vercel.app`) — ⭐ the team's **Source of Truth** for reporting/reconciliation.
- **Automations** — n8n workflows (Booking Sync, GHL→Sales, Source Data, Daily Report→Discord, Google Ads→Marketing), Zapier (BL→Sheets), BookingLayer scheduled CSVs, Apps Scripts (source categorization, date fixes, tracker rebuilds, live sales/revenue attribution), GHL (CRM/calendars), Discord daily reports.
- **Technologist support** — Saul/Jacobo handle hands-on GHL/tech setup; the role directs it.

### E. Strategy, Reporting & Commissions
- **Weekly leadership report** — the recurring exec report (fixed section order, mines WhatsApp + MTD numbers).
- **Two monthly commission runs** — (1) **media-buyer** commissions by lead-create date; (2) **sales-rep** commissions by close. Both in Martech SOP §12 (Part A / Part B).
- **Strategic projects** — funnels/CRO, landing pages, pixel/CAPI, app/membership model, B2B, Airbnb/cabin rentals, website health (the new site hurt organic conversions — live watch item).

---

## 4. The Ongoing Work (Daily / Weekly / Monthly)

### Daily
- **Ads (per platform GG/FB):** spend updated, calls updated, sales + revenue updated.
- **Sales by Source:** all new bookings present, sources populated.
- **Sales Dashboard:** calls updated for **both** regular + FB calendars, outcomes updated, sales + revenue accurate.
- **Rep performance:** glance at the Discord sales reports; is the team on pace for the month's show/close rates?
- **AI SMS setter:** quick inbox audit.
- Watch for the known pipeline failure modes: FB/GG "row burial," the Google Ads Script not firing, expired n8n/GHL/Sheets credentials.

### Weekly
- **Generate the weekly leadership report** (order: Community → Integration → Paid Ads → Sales → Mar Tech → Reddit → Email → Website → B2B → SEO → Organic Social → Podcast → Airbnb → App/Membership last).
- **Sales by Source sync** — paste the two fresh BL exports into helper tabs, run the sync + source-category scripts.
- **Sales tab maintenance** ritual (brittle → human-in-the-loop).
- **Content** review/approval; keep cadence on track.
- **Calendar/roster check** with the sales team.

### Monthly
- **Media-buyer commissions** — BL export → lead-attribution cross-reference → check Juan's dashboard (FB) + Sales-by-Source → drop pending/$0 → pay by buyer.
- **Sales-rep commissions** — sum Sales Dashboard revenue by rep, apply each rep's %.
- **Rebuild the Rep Monthly Breakdown** tab at the start of each month (not on a trigger — it lags if skipped).
- **Team:** monthly sales meeting + 1-on-1s.
- Sanity-check Marketing MTD Sales/Revenue vs. Google-Ads paid bookings in Raw Bookings.

---

## 5. Systems & Access

| System | Purpose |
|---|---|
| Google Ads (629-914-3676) | Spend/leads + daily Marketing Dashboard Script |
| Meta Ads + Pixel/CAPI | Facebook campaigns, conversion tracking |
| Google Sheets (Marketing, Sales, Sales by Source, GG Leads) | Data layer behind every dashboard |
| Vercel Dashboard | ⭐ Source of Truth |
| n8n (`server.lawayraserver.com`) | Sync/report automations |
| Zapier | BookingLayer → Sheets |
| BookingLayer | Bookings + "How did you hear?" source data |
| GoHighLevel (GHL) | CRM, calendars, appointment outcomes, AI SMS setter |
| Circle | Community platform |
| Discord | Automated daily marketing + sales reports |
| Upload-Post + Content Machine | Social content production/scheduling |

All logins on `admin@lawayra.com`; passwords in the team password manager. Canonical logins/automations cheat sheet = the **Martech SOP**.

---

## 6. Resource Directory — Every Link Aliyah Needs

*All logins are on `admin@lawayra.com`; passwords live in the team password manager (never shared in this doc).*

### SOPs (how to do the work)
| SOP | Link |
|---|---|
| Mar Tech SOP (canonical) | https://marcuswest-lab.github.io/lawayra-sops/lawayra-martech-sop.html |
| Mar Tech SOP (old, archived) | https://docs.google.com/document/d/1QRYCNmiEnAS4E0VWRSzMhNRR0EPoAXizuu0hzwwzDfo/edit |
| Community SOP | https://marcuswest-lab.github.io/lawayra-sops/lawayra-community-sops.html |
| Content SOP | https://marcuswest-lab.github.io/lawayra-content-strategy/ |
| Google Media Buyer SOP | https://docs.google.com/document/d/1eI7ELV3Y8NWBOK0LqEZ-8US-QuHtqGSxVwBh94qvPpo/edit |
| Head of Sales — Roles & Responsibilities | https://docs.google.com/document/d/11-qI94ikm7MGJRTxqZsdM0nSVSQHqoU6GMZPjmS0HGM/edit |
| Sales Rep SOP | https://docs.google.com/document/d/1xJTsHfawFyFr6Fjb2GTEMwmlpuCyICnhVCHxngNbjH4/edit |
| Email Welcome Sequence (40 emails) | https://docs.google.com/document/d/199h47lPuh0o-f7RIaTzPIO_sWZ2u7pGfb_e-9wI7U6A/edit |
| Set up a new sales rep in GHL (Loom) | https://www.loom.com/share/798f9a323fcf48b1b1745800fe9f791e |
| Media-buyer commission process (Loom) | https://www.loom.com/share/72bec0ede537409dbc886f21538307f3 |

### Planning, Org & Updates
| Doc | Link |
|---|---|
| Marketing & Sales Dept — Org Chart + SOPs + Meeting Notes (hub) | https://docs.google.com/document/d/1JiMPulkpl_fieE0HWkthMY2ch_2_wYlbaHGM5_W5Vdg/edit |
| Marketing Project Management Calendar | https://docs.google.com/spreadsheets/d/1svirDMQDzjRx_EAP6zmuPCK4V88lr02mNS4JFla4YDw/edit |
| Marketing & Sales Updates (weekly log) | https://docs.google.com/document/d/1ruQMif1-kbtRaCa7DH9nQGo6QHymdl55DCMjRmjU4w0/edit |

### Meeting Notes (running context)
| Notes | Link |
|---|---|
| Marketing & Sales Annual Reports (2024–2025 Summary) | https://docs.google.com/document/d/1aobr8XltrJp1DAYrXjSqJhLsvMEykTK25sykSiNZ3fo/edit |
| Paid Ads & Sales Meeting Notes | https://docs.google.com/document/d/1MynYexZJ0TC2DDuJkzJtdrTtD2RF3V6wu-aAEV8W-ws/edit |
| Mar Tech Meeting Notes | https://docs.google.com/document/d/1zpHeNkYuRoSTtVvCIjkn66tmMZas1URS808xoZrPsOA/edit |
| SEO Meeting Notes | https://docs.google.com/document/d/1uUq46Jh0n9INAhiALMMecTPvgaq-DKvN6wgYIaFBC9k/edit |
| Circle Community Meeting Notes | https://docs.google.com/document/d/1jFJb4s9NixnpTTqOghpjGQ6BJm-UnueLefz6SmB104s/edit |

### Dashboards & Reporting
| Dashboard | Link |
|---|---|
| ⭐ Marketing/Sales Dashboard — Vercel (Source of Truth) | https://lw-sales-dashboard.vercel.app/ |
| Juan's Meta Ads Dashboard | https://script.google.com/macros/s/AKfycbzL5hZgGHryjPvDzonlKvH-DaTUwhjQ0SHahCJmf7p-XcuQ1gojCr4WnLkSNZTll2lW/exec?v=5 |
| Sales Dashboard (sheet) | https://docs.google.com/spreadsheets/d/1fcBghq6dXp9v_58Lz0b-Fm5iXYlhw4HF00zQUjCSSTU/edit |
| Ads / Marketing Dashboard (sheet) | https://docs.google.com/spreadsheets/d/1du8jYw-EPr3Bvkiq-_sMsA8XNtWH-d81AXS48glVzvc/edit |
| Sales by Source — Raw Bookings (sheet) | https://docs.google.com/spreadsheets/d/139G-OUoApI5ksdSMXMe_WE8geaw_mZ3Sv8PYvBDsq5w/edit |
| GG Leads (Google Ads lead emails) | https://docs.google.com/spreadsheets/d/1PKOKpTg9o6HgV41Fvwag8aId5PAnr4qH5AwxmVL2jBg/edit |
| Old Sales Tracking Sheet (read-only ref) | https://docs.google.com/spreadsheets/d/16fy6Fpq7Z6P3yv3JN0YzmxlT204gnrfThu8KcC13gnY/edit |

### Tools & Platforms (logins)
| Platform | Link |
|---|---|
| n8n (automations) | https://server.lawayraserver.com/home/workflows |
| Zapier (BL → Sheets Zap) | https://zapier.com/editor/356749217/published/ |
| BookingLayer | https://app.bookinglayer.io |
| GoHighLevel (CRM/calendars/AI SMS) | https://app.gohighlevel.com |
| Circle (community) | https://lawayra-family.circle.so/feed |
| Website | https://ayahuascaincolombia.com |
| Instagram | https://instagram.com/lawayra_retreat |

**BookingLayer scheduled reports** (feed the source pipeline):
- "How did you hear?": https://app.bookinglayer.io/reports_v2/edit/019ca9d3-8267-72dd-87c9-a8be89b7095d
- Email/Person export: https://app.bookinglayer.io/reports_v2/edit/019d83e7-9b53-730a-b26a-f1f8b890fbe5

### Discord (daily automated reports)
- Sales-team Discord server (daily sales reports): https://discord.gg/yctYJzP5NM
- `#gg-marketing-tracking` — daily Google Ads / marketing report
- `#sales-tracking` — daily sales-call report

### Internal Repo Docs (deeper reference)
`CLAUDE.md` · `DASHBOARDS_MASTER.md` · `SALES_TRACKING_SYSTEM.md` · `SALES_DASHBOARD_README.md` · `SALES_BY_SOURCE_RUNBOOK.md`

---

*Bottom line: the Head of Growth owns the number — making sure spend turns into leads, leads into booked calls, calls into closed retreats — and that every step is measured, attributed, reported, and staffed. Aliyah already runs the closing half; stepping into Growth means also owning the acquisition, nurture, and mar-tech halves that feed it.*
