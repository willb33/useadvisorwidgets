# The Solo Ledger

A four-calculator suite for the self-employed: Solo 401(k) contributions,
self-employment tax, SEP IRA vs. Solo 401(k) comparison, and true take-home pay.

## Local development
```
npm install
npm run dev
```

## Build for production
```
npm run build
```
Output goes to `dist/` — deploy that folder to Cloudflare Pages
(or connect this repo directly and Cloudflare will run `npm run build` for you).

## Before going live
- Update `site` in `astro.config.mjs` to your real domain
- Point your domain's DNS at Cloudflare Pages
- Double check the 2026 tax figures against the IRS before the next tax year —
  they're hardcoded in each calculator's script and will need a yearly refresh
