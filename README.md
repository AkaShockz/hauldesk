# Hauldesk

Go-to-market pack for selling a **private multi-workflow automation desk** to UK vehicle logistics teams.

Working brand: **Hauldesk**. Pilot offer: **£2,500 + £149/mo hosting** to get the desk live with the first module. Extra modules scoped after that.

This repo is intentionally separate from any client production app. Do not put customer job data here.

## Positioning

Hauldesk is **not** a single job-sheet converter. It is a company-private desk where many automations stack:

- Job sheet / manifest → planner Excel  
- Address & postcode checks  
- Customer-format normalisers  
- Board merge & exceptions  
- Ready-by / chase lists  
- Other repeat allocator workflows once samples exist  

Lead with the desk. Use job sheets as a common first example — never as the whole product.

## Contents

| File | Use |
|------|-----|
| `landing.html` | One-page site with multi-module desk demo — replace `YOU@EXAMPLE.com`, then host |
| `linkedin-outreach.md` | Connection notes + follow-ups |
| `email-outreach.md` | Cold email + post-sample reply |
| `pilot-proposal.md` | Send same day after a good discovery call |
| `targets.csv` | Track ~40 firms (segment, hook, status, next action) |

## Quick start

1. Find-replace `YOU@EXAMPLE.com` with your real email (optional Calendly on landing CTAs).
2. Open `landing.html` — flip module tabs, try sample chips, live parse, upload, filters, copy/CSV.
3. Host on Netlify Drop / Cloudflare Pages / any static host.
4. Record a short Loom showing the desk modules, not only job-sheet parse.
5. Fill `targets.csv` and send ~10 personalised LinkedIn notes per day.

## Suggested weekly rhythm

| Day focus | Activity |
|-----------|----------|
| Research | Add 8–10 firms with a real hook |
| Outbound | 10 LinkedIn notes or 5 emails |
| Follow-up | Day-3 / day-7 bumps; free sample within 48h |
| Close | After a call, send `pilot-proposal.md` the same day |

## Status values (`targets.csv`)

`not_contacted` → `connected` / `emailed` → `sample_sent` → `call_booked` → `pilot_proposed` → `won` / `lost` / `nurture`

Useful `segment` values: `trade_plate`, `inspect_collect`, `transporter`, `dealer_handover`, `compound`, `mixed_ops`

## Boundaries

- Sell a **new** private build per customer — not access to another client’s system.
- Prefer paid pilots over free “full platform” builds.
- Keep real customer formats and data out of this marketing repo.
- Free sample = redacted data only; delete files after you return the test output.
- Landing job-sheet panel is one interactive example — production modules are scoped per customer.
