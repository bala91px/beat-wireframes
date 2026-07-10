# Beat — Rep App · Wireframe Preview

Clickable wireframes for **Beat**, a mobile-first field sales rep ordering app (South Africa FMCG market). Two design directions for review.

> **Confidential.** Shared for client review only. Not for redistribution.

## 🔗 Live preview

**→ https://bala91px.github.io/beat-wireframes/**

Open the link, then pick a version. Every screen is interactive — works on phone or desktop.

## Versions

| | Direction | What it shows | Open |
|---|---|---|---|
| **Version 1** | Catalog · Weight · Discounts | Fuller catalog flow — category navigator with search, fast-moving flags and regional availability; loud bulk discounts; package sizing with live order weight and load class; persistent cart. | [`v1.html`](v1.html) |
| **Version 2** | Full-page Quick Add | Streamlined flow — reels-style hero feed (one product per screen) opening into a single scrolling page: container → quantity (quick chips + custom) → order summary, with auto-scroll between steps. | [`v2.html`](v2.html) |

## 📋 Product Requirements Document (PRD v1)

**→ https://bala91px.github.io/beat-wireframes/prd.html**

High-level build spec for the full-stack developer: platform &amp; stack decision (installable PWA, tablet-first, Next.js + Supabase), actors, rep-app &amp; admin feature specs (numbered requirements, e.g. `R-C1`, `A-T2`), data model, pricing-engine rules, non-functional requirements, and what's explicitly out of scope for MVP vs Phase 2. Sticky section nav, no build step.

## 🎬 Internal demo — Social Demo (Director's Commentary)

**Not linked from the page above.** This is a separate, unlisted page for Bala's own demo/portfolio-video recording — **do not send this link to the client.** It embeds both prototypes in one shell with a live version switcher and toggleable commentary layers (UX, Growth/Psychology, Co-founder Strategy) plus a "Client Mode" that strips all of it back to the clean phone.

**→ https://bala91px.github.io/beat-wireframes/social-demo.html**

- Switch **V2 · Catalog** ↔ **V4 · Quick-Add** live, same commentary system wraps both.
- ⚙️ Settings: Client Mode (master hide), Rep-flow rail, and the 3 lenses — state persists across reloads for a stable shoot.
- A live interaction-cost meter on V4 counts taps to a priced order (vs. the old stepper flow).
- Because this repo is **public**, the URL isn't secret — it's just unlisted (not linked, `noindex`). Treat it as private-by-obscurity, not access-controlled.

## Notes

- Wireframes use **placeholder data** (dummy brand + generic SKUs) — no live catalog or pricing.
- Currency shown in ₹ for the demo; swappable per market.
- Static HTML — no build step, no dependencies.

## Contents

```
index.html          landing page (pick a version) — the client-facing link
v1.html              Version 1 — Catalog · Weight · Discounts
v2.html              Version 2 — Full-page Quick Add
prd.html             Product Requirements Document v1 — for the full-stack developer
social-demo.html     INTERNAL — Director's Commentary shell (not linked from index.html)
demo-catalog.html    internal dependency of social-demo.html (Catalog prototype, embedded)
demo-quickadd.html   internal dependency of social-demo.html (Quick-Add prototype, embedded)
```

---

© 2026 **91Pixels**. All rights reserved. See [LICENSE](LICENSE).
