# بُنيان — Bonyan Construction Marketplace Demo

Interactive Arabic RTL product concept for a Saudi construction-services marketplace.

## Concept
**Standardize → Match → Price → Compare → Contract → Manage**

A customer describes a project once. The platform creates a standardized scope, checks provider eligibility, calculates demo pricing using provider-specific rules, compares equivalent offers, and demonstrates a path from quotation to contracting and project tracking.

## Included scenarios
- New villa
- Turnkey villa
- Design & permitting only
- Execution with ready drawings/BOQ
- Renovation
- Additional floor/annex
- Residential building

## Demo logic
Engineering pricing uses configurable base packages, incremental built-area pricing and add-ons (BOQ, supervision, pool, basement, elevator, urgency). Construction estimates use provider-specific rates adjusted by finish level and complexity.

**Important:** All provider names, prices, ratings, licence-like identifiers and commercial terms are fictional demo data. Construction estimates before final drawings/BOQ are explicitly presented as preliminary estimates, not binding quotations.

## Saudi workflow framing
The demo is designed to orchestrate a customer journey around engineering offices, contractors, scope, quotations, contracts and project milestones. It does **not** claim to replace official municipal/regulatory processes. Production launch would require regulatory/legal review and integrations where appropriate.

## Run
Static HTML/CSS/JS. Open `index.html` locally or publish with GitHub Pages.

## GitHub Pages
Repository Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

Expected URL:
`https://a81927788.github.io/bonyan-demo/`

## Files
- `index.html` — product experience and all views
- `styles.css` — responsive Arabic RTL UI
- `app.js` — scenarios, pricing, matching, comparison and quote/contract interactions
- `.nojekyll` — GitHub Pages static publishing helper

Demo v1.0 — September 2026
