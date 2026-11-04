# Hauldesk

Go-to-market pack for selling **private ops automation desks** to UK vehicle logistics teams — trade plate, inspect & collect, transporter, and dealer-handover work.

Working brand: **Hauldesk**. Pilot offer: **£2,500 + £149/mo hosting** for the first module on a private desk. Extra modules scoped after that.

This repo is intentionally separate from any client production app. Do not put customer job data here.

## Positioning

Hauldesk is a company-private desk where automations stack over time:

1. **First module (pilot):** usually job sheet → allocator Excel  
2. **Later modules:** address checks, customer-format normalisers, board merges, exception flags, other repeatable ops workflows

Lead with the painful first workflow. Sell the desk that can grow.

## Contents

| File | Use |
|------|-----|
| `landing.html` | One-page site with live Module 01 demo — replace `YOU@EXAMPLE.com`, then host |
| `linkedin-outreach.md` | Connection notes + follow-ups |
| `email-outreach.md` | Cold email + post-sample reply |
| `pilot-proposal.md` | Send same day after a good discovery call |
| `targets.csv` | Track ~40 firms (segment, hook, status, next action) |

## Quick start

1. Find-replace `YOU@EXAMPLE.com` with your real email (optional Calendly on landing CTAs).
2. Open `landing.html` locally — try **Mixed morning** / **Trade plate** / **Inspect & collect** / **Transporter**, then **Download CSV**.
3. Host on Netlify Drop / Cloudflare Pages / any static host.
4. Record a 45s Loom (redacted sample only) showing paste → preview → Excel, then mention “same desk, more modules later”.
5. Fill `targets.csv` and send ~10 personalised LinkedIn notes per day.

## Suggested weekly rhythm

| Day focus | Activity |
|-----------|----------|
| Research | Add 8–10 firms with a real hook |
| Outbound | 10 LinkedIn notes or 5 emails |
| Follow-up | Day-3 / day-7 bumps; free parse within 48h |
| Close | After a call, send `pilot-proposal.md` the same day |

## Status values (`targets.csv`)

`not_contacted` → `connected` / `emailed` → `sample_sent` → `call_booked` → `pilot_proposed` → `won` / `lost` / `nurture`

Useful `segment` values: `trade_plate`, `inspect_collect`, `transporter`, `dealer_handover`, `compound`, `mixed_ops`

## Boundaries

- Sell a **new** private build per customer — not access to another client’s system.
- Prefer paid pilots over free “full platform” builds.
- Keep real customer formats and data out of this marketing repo.
- Free parse = redacted samples only; delete files after you return the test output.
- Landing demo is Module 01 only — production parsers and later modules are scoped per customer.
