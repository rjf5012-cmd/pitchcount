# PitchCountCalculator.com

A simple, fast youth baseball **pitch count and rest day calculator** designed for coaches and parents.

Deployed on **Cloudflare Pages** at:

> https://pitchcountcalculator.com/

## Files

- `index.html`  
  Main one-page app with:
  - Pitch count calculator
  - Age-based max pitch limits
  - Rest day calculation
  - “Share this with your league” button
  - SEO meta tags, OpenGraph, FAQ schema

- `rest-day-chart.html`  
  Static reference page showing a simple youth pitching rest day chart.

- `pitch-count-rules.html`  
  Short explainer on why pitch count rules exist and how to apply them.

- `little-league-pitching-rules.html`  
  Overview of common Little League–style pitching rules and daily limits.

- `robots.txt`  
  Allows indexing and points crawlers to the sitemap.

- `sitemap.xml`  
  Lists the primary pages for search engines.

- `favicon.svg`  
  Simple baseball-themed favicon.

## Deployment (Cloudflare Pages)

1. Push this repo to GitHub.
2. In Cloudflare Pages:
   - Create a new project.
   - Connect to this repo.
   - Set the build command to **none** (static site).
   - Set the output directory to `/` (root).
3. Add the custom domain `pitchcountcalculator.com` and update your DNS as instructed.

## Notes

- This site is informational only and does **not** replace medical advice.
- Always follow your league’s official pitching rules and guidelines.
