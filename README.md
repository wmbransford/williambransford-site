# williambransford-site

Source for [williambransford.com](https://williambransford.com) — William's personal-brand site. Two offers: Advisory ($5k/mo) and Build Club ($99/mo). Separate from [Space Studios](https://spacestudios.us); shared typography + component DNA, distinct brand identity.

## Stack
- Plain HTML + hand-rolled CSS. No build step, no framework, no bundler.
- Hosted on GitHub Pages, served from `main` root.
- Shared fonts: Inter (body), Fraunces (display serif), JetBrains Mono (micro-type).
- Palette: warm off-white + ember amber (distinct from Space Studios' dark + cyan).

## Local preview
Open `index.html` in a browser. Each subpath (`/advisory/`, `/build-club/`) resolves via its own `index.html`.

## Deploy
Push to `main`. GitHub Pages serves the root.

## Structure
- `index.html` — homepage, dual-path CTAs.
- `advisory/index.html` — $5k/mo advisory offer page.
- `build-club/index.html` — $99/mo build club offer page.
- `404.html` — custom not-found.
- `assets/style.css` — shared stylesheet for all pages.
- `assets/william-bransford.jpg` — founder portrait (borrowed from Space Studios).
- `CNAME` — custom domain marker, activated at DNS cutover.

## Wiring to do post-approval
- **Advisory application**: `advisory/index.html` CTA currently opens a pre-filled `mailto:william@spacestudios.us` — swap to Google Form URL once created.
- **Build Club payment**: `build-club/index.html` CTA currently opens `mailto:william@spacestudios.us` ("early access list") — swap to live Stripe Payment Link once product is created.

## Brand direction
- **Shared with Space Studios:** Inter + JetBrains Mono, hairline grids, button system, section structure.
- **Distinct:** Warm light theme (#f7f3ec), ember amber accent (#b8451a), Fraunces display serif for headlines, voicier first-person tone.
