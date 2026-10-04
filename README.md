# QuickCalc

A free, fast collection of calculators built to answer the exact math questions people search for every day — no sign-up, no clutter, instant answers.

**Live site:** https://ronak07-cell.github.io/solid-dollop/

## Calculators

- **Percentage Calculator** — "what is X% of Y" and "X is what % of Y"
- **CGPA to Percentage** — supports both the CBSE standard (×9.5) and ×10 formulas used by different institutions
- **BMI Calculator** — with weight category classification
- **Age Calculator** — exact age in years, months, and days from date of birth

## Features

- Zero backend — pure HTML, CSS, and vanilla JavaScript
- Calculation history saved per-calculator via `localStorage`, persists across visits
- Fully responsive, mobile-first design
- SEO-ready: meta descriptions, sitemap.xml, robots.txt, Google Search Console verified
- Google Analytics integrated for traffic insight

## Tech stack

Plain HTML/CSS/JavaScript — no frameworks, no build step, no dependencies. Hosted free on GitHub Pages, auto-deploying on every push to `main`.

## Project structure
index.html — Percentage calculator (homepage)
cgpa.html — CGPA to percentage calculator
bmi.html — BMI calculator
age.html — Age calculator
about.html — About page
contact.html — Contact page
privacy.html — Privacy policy
sitemap.xml — Search engine sitemap
robots.txt — Crawler rules

## What I learned

- Building a real, deployed, multi-page website from scratch with no frameworks
- `localStorage` for client-side persistence without a backend
- The full SEO/discoverability pipeline: meta tags, sitemaps, robots.txt, Google Search Console verification and indexing requests
- GitHub Pages deployment and its automatic build-on-push workflow
- Google Analytics integration for real visitor tracking
- Debugging a GitHub Pages first-deploy issue by diagnosing through GitHub Actions directly

## Future plans

- Additional calculators based on search demand
- Google AdSense integration once the site has established organic traffic
- Possible custom domain