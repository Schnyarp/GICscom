# GICs.com

A conservative, Canada-focused landing page for comparing indicative GIC rates and collecting early-access / quote requests.

## What this site is
GICs.com is designed to:
- Present a clean, bank-like overview of common GIC terms (e.g., 1/3/5 year)
- Set expectations clearly (indicative/sample rates until live data is available)
- Capture “early access” interest and inbound quote requests

## Current pages
- `/` — Landing page (Coming Soon + early access form + sample indicative rate table)

## Files
- `index.html` — Single-page landing page (static HTML + CSS)

## Deploy
This site is static and can be deployed on any static host, including:
- Cloudflare Pages
- Netlify
- Vercel
- S3 + CloudFront

### Basic local preview
Open `index.html` in a browser, or serve the directory:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Roadmap (suggested)
- Replace sample institutions and rates with real values and add an “as of” date
- Add dedicated pages:
  - `/rates/` (or term-specific pages like `/rates/1-year/`)
  - `/about/`
  - `/contact/`
  - `/privacy/` and `/terms/`
- Add form handling (email/CRM) and spam protection (e.g., honeypot + rate limiting)
- Add analytics + basic SEO metadata (OpenGraph / Twitter cards)

## Notes
- This repository contains presentation only. Any quote fulfillment, financial advice, or brokering must be handled by appropriate licensed parties and compliant workflows.