# Origin Performance International

Company website for **Oarigin Performance International**, a rowing performance coaching company in South Florida. Coaching staff includes Emre CIKINCI, former Turkish National Team rower and youth & junior coach at North Palm Beach Rowing Club (NPBRC).

**Live site:** https://oariginperformanceinternational.com

## Stack
Static HTML/CSS/JS — no build step, no backend. Hosted on GitHub Pages.

## Structure
- `index.html` — single-page site
- `images/` — coaching photos
- `CNAME` — custom domain pointer for GitHub Pages
- `robots.txt`, `sitemap.xml` — SEO basics

## Deploy
Push to `main`. GitHub Pages auto-deploys from the root of the branch.

## Previous version
The original coach-profile version (before the 2026-09-29 company rebrand) is saved as tag `v1-emre-profile` and branch `backup/v1-emre-profile`.
To restore it on the live site:
```
git checkout main && git checkout v1-emre-profile -- . && git commit -m "Restore v1 profile version" && git push
```
