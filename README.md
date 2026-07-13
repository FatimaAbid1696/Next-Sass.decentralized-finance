# Nexsas — DeFi Landing Website

A responsive, multi-page website for "Nexsas" (decentralized finance platform), built as an internship task clone of the reference design.

## Folder structure

```
nexsas-website/
├── index.html       → Homepage (hero, features, stats, testimonials, blog, CTA, footer)
├── services.html     → Services page (linked from "Explore the platform")
├── pricing.html       → Pricing page (linked from the "Pricing" nav item)
├── style.css          → Shared stylesheet for all pages (colors, layout, components, dark mode)
├── script.js          → Shared JavaScript (mobile menu, mega-menu dropdowns, dark mode, pricing toggle, FAQ accordion)
├── assets/            → Folder for any local images/icons if you replace the placeholder ones
└── README.md          → This file
```

## Features

- **Mega-menu dropdowns** — "Company", "Platform", and "Resources" in the nav open a 2-column menu on hover (desktop) or tap-to-expand accordion (mobile), each with icons, titles, and short descriptions.
- **Pricing page** — 3 plans (Starter / Pro / Enterprise) with a working Monthly/Yearly billing toggle, a feature comparison table, and an FAQ accordion.
- **Dark mode** — toggle in the bottom-right corner, remembers your preference.
- **Moving avatar marquee** — auto-scrolling row of avatars under the testimonials quote.
- Fully responsive: mobile, tablet, and desktop layouts.

## How to view it

No build tools or installs needed — it's plain HTML/CSS/JS.

1. Download/extract the whole `nexsas-website` folder.
2. Double-click `index.html` to open it in any browser.
3. Click around — "Explore the platform" links to `services.html`.

## Notes

- Images (avatars, blog photos) currently load from placeholder services (`pravatar.cc`, `unsplash.com`) since no real assets were provided. Replace the `src` links in the HTML with files placed in `/assets` if you want fully local/offline images.
- Pricing shown ($0 / $29 / Custom) is placeholder — swap in your real plan names and prices in `pricing.html`.

## Tech used

- HTML5
- CSS3 (custom properties / CSS variables, flexbox, grid, animations)
- Vanilla JavaScript (no frameworks or build step)
