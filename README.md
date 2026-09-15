# Company AI Architect — Operator sales desk

Public front desk / discovery demo for **Company AI Architect** (Operator sales asset). Static HTML/CSS/JS. No SaaS backend. Product engine stays LAN-only.

## Live

| Role | URL |
|------|-----|
| Canonical | https://companyaiarchitect.com (→ www) |
| Vercel mirror | https://k3-architect-story.vercel.app |
| GitHub Pages (this repo) | https://joshtitan88-collab.github.io/k3-architect-story/ |
| Older Pages mirror | https://joshtitan88-collab.github.io/company-ai-architect/ |

## What visitors get

- Talk-or-type desk (`public/desk.js`) that books a free 30-minute discovery via mailto
- Pricing / privacy / capabilities answers from on-page copy (no invented clients beyond Acme HVAC in older story docs)
- Privacy page; no analytics pixel, no form backend

## Local preview (free)

```bash
python3 -m http.server 8765 --directory public
# open http://127.0.0.1:8765/
```

Working tree: `public/`. Deploy source for Vercel + GitHub Pages Actions is that folder.

## Not in scope

- Rebuilding Company AI Architect product / CAA app
- New SaaS, auth, or paid hosting beyond existing Vercel/Pages
