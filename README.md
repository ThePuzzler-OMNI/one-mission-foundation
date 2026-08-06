# One Mission Foundation

Static public surface for body · place · circadian continuity under One Mission.

**Primary domain:** onemissionfoundation.org  
**Role:** Adam garden — life proliferation, stewardship of the dwelling, high-frequency biology posture.

## Stack

- Static HTML + Tailwind CDN (optional; layout/chrome **not** Tailwind-only)
- Fonts: Cormorant Garamond (display) + DM Sans
- Colors: ink / warm parchment / **apple** red / cider / mist (apple-warm family — not hive gold primary)
- Vercel (Framework: Other, no build)

## Network template kit (Q-NET-ADOPT-F · 2026-08-05)

Aligned to `product/docs/NETWORK_TEMPLATE_KIT_v1_2026-08-05.md`:

| Rule | Foundation |
|------|------------|
| `--page-max: 56rem` | `css/page-layout.css` |
| Explicit chrome CSS | `js/site-chrome.js` |
| Desktop hamburger always on | yes |
| Sisters omit self | registry + runtime filter |
| Accent | apple `#d94a38` (not hive) |

Smoke after deploy: https://onemissionfoundation.org/ · desktop hamburger · Escape closes menu · footer sisters = OM · Intek · IMI · Exchange (no Foundation self).

## Pages

| Path | Job |
|------|-----|
| `/` | Home — three doors, standing sentence, sister brands |
| `/posture` | Why this surface exists · HOG as intellectual discipline only |
| `/practices` | Flip times · movement · recovery · substances · nutrition |
| `/place` | Circadian architecture · dwelling as medium |
| `/refused` | Permanent boundaries (control on marketing) |
| `/network` | Sister sites |

## Deploy

1. Create GitHub repo (e.g. `ThePuzzler-OMNI/one-mission-foundation`)
2. Push this tree
3. Vercel → New Project → Import → Framework Other, no build
4. Add domain `onemissionfoundation.org`
5. GoDaddy DNS:
   - A `@` → `76.76.21.21`
   - CNAME `www` → `cname.vercel-dns.com`
6. SSL auto-provisions

## Pack aliases

Forward `.com` · `.net` · `.info` · `.store` · `.shop` to `.org` when ready.

## Not in this ship

- Consilientism daily surface (consilientism.org / .com) — staged
- Analytics (add analytics.js pattern from sister sites later)
- Live forms or membership

## Refused

See `refused.html`. No medical claims. No HOG-proves-diet. No wellness fashion.
