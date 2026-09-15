# STATUS — P1.3 k3-architect-story

**Date:** 2026-09-15 (America/New_York)  
**Verdict:** **DONE — useful Operator sales asset; light polish applied (local only).**  
**ROI:** Keep. Do not skip. Do not rebuild CAA. Do not start P2 from this ticket.

## Assessment

Yes — supports Operator sales as the public **desk / discovery demo** for Company AI Architect.

- Live canonical: https://companyaiarchitect.com → https://www.companyaiarchitect.com (200, desk UI + `desk.js`)
- Mirrors: Vercel project + GitHub Pages from `public/`
- Static only; mailto booking; no SaaS; product stays LAN-only
- Smoke: local `python3 -m http.server` serves index, assets, desk.js, privacy (all 200)

## Polish applied (small; no deep rewrite)

| Change | Why |
|--------|-----|
| `README.md` clarified | Operator sales role, live URLs, local preview, out-of-scope |
| `privacy.html` / `404.html` `#unlock` → `#desk` | Broken CTA after desk-first redesign |
| `404.html` “story” → “desk” | Match current product language |
| `vercel.json` + `public/vercel.json` Permissions-Policy | Repo denied mic; live www already allows `microphone=(self)` for Mic |

## Not done / blocked

- **Not pushed** to GitHub (commit/push not requested). Live site already has correct mic policy; broken `#unlock` links still on deployed privacy/404 until push+deploy.
- Leftover one-scroll story code (`public/app.js`, unused hero/room/package assets, unlock CSS) left in place — cleanup is P2+ / low priority, not this ticket.
- No CAA rebuild. No new hosting. No deep copy rewrite.

## Parent / Assay ping

P1.3 complete locally. Sales-useful. Push when Operator wants privacy/404 CTA fix live.
