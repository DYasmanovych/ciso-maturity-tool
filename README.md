# Security Maturity Assessment

A free, open-source dashboard to assess the maturity of your information security program across **19 foundational processes** — from Onboarding and Awareness to Incident Response, CI/CD, TPRM, and Cryptography.

Built for CISOs, security leads, and anyone shaping a security strategy who's tired of bloated GRC tools and dead Excel files.

<img width="1242" height="946" alt="pewview-gh" src="https://github.com/user-attachments/assets/a04aff5b-3eb0-45e6-92c6-2027ee62d8ca" />

## Why this exists

When you start building a security program, the first question is always: **where are we today?**

Most teams answer this with a multi-week interview marathon and a 200-row spreadsheet that nobody opens twice. This tool turns the same exercise into a 1-hour focused session with a clear visual outcome you can show to leadership the same day.

## What it does

- **19 security processes**, each with 5 carefully written questions
- **L1 → L5 maturity rubric** (Initial → Repeatable → Defined → Managed → Optimized) based on CMMI conventions
- **Interactive dashboard** with radar chart, top gaps, and per-process breakdown
- **Set your own 12-month target** for each process
- **Notes / evidence field** per question — useful when you go for ISO 27001 or SOC 2 later
- **Auto-saves** to your browser — close the tab and come back, everything's still there
- **Export / Import JSON** for backups and team handoffs
- **Print mode** for clean PDF reports
- **100% local** — nothing leaves your browser, no signup, no telemetry

## How to use

### Single file, works offline

1. Download `maturity-assessment-OFFLINE.html`
2. Double-click to open in Chrome / Safari / Firefox
3. Enter your company name and start scoring

That's it. No installation, no internet required.

## The 19 processes covered

| # | Process | # | Process |
|---|---|---|---|
| 1 | Onboarding | 11 | Endpoint Security |
| 2 | Offboarding | 12 | Change Management |
| 3 | Awareness | 13 | Legal Review |
| 4 | Technical Testing | 14 | Threat Intelligence |
| 5 | Incident Response | 15 | Logging & Monitoring |
| 6 | Risk Assessment | 16 | Data Protection & Privacy |
| 7 | TPRM | 17 | Business Continuity & DR |
| 8 | Compliance | 18 | Physical Security |
| 9 | CI/CD Pipeline | 19 | Cryptography & Key Mgmt |
| 10 | Roles & Responsibilities | | |

## Maturity scale

| Level | Name | Meaning |
|---|---|---|
| **L1** | Initial | Process exists chaotically or not at all. Reactive, depends on individuals |
| **L2** | Repeatable | Performed but informally. Quality depends on the person doing it |
| **L3** | Defined | Documented, standardized, has an owner. Evidence exists |
| **L4** | Managed | Measured with metrics. SLAs/KPIs. Deviations corrected |
| **L5** | Optimized | Continuously improved. Integrated with business outcomes |

## Recommended workflow

1. **Self-score first** (1-2 hours, alone) — be honest, not aspirational
2. **Validate with stakeholders** — IT lead, HR, Legal, B2B/Sales lead. Where their scores diverge from yours, dig in. Divergence is a finding.
3. **Set 12-month targets** — realistic goals: L3 for most processes, L4 for Incident Response and CI/CD if you're a security-sensitive business
4. **Export the JSON** as a baseline
5. **Re-score quarterly** — track progress as evidence the program works

## Privacy

All data is stored in your browser's `localStorage`. Nothing is sent anywhere. No analytics, no cookies, no servers. Use **Export** to back up your data as a JSON file. Use **Import** to restore on another machine.

## Contributing

Open an issue or PR if you want to:
- Add or improve questions
- Suggest a missing process
- Translate to another language
- Improve the design

## License

MIT — use freely, fork freely, ship freely.
