# FragranceBuy.ca — Homepage Redesign Concept (Prototype A)

A deal-led homepage redesign concept for **FragranceBuy.ca**, a Canadian online discount fragrance retailer. Built as a single, self-contained HTML file — no build step and nothing to install.

> **Unofficial concept / portfolio piece.** Not affiliated with or endorsed by FragranceBuy.ca. Some prices and figures are illustrative, and product photos are referenced from FragranceBuy's public CDN for demonstration only.

## View it

- **Locally:** open `index.html` in any modern browser.
- **Online:** deploy to any static host (see below).

## What's inside

A full conversion-focused homepage:

- Rotating announcement bar and a sticky header with search
- Deal-led hero with a featured bottle on a lit "stage"
- Trust bar, a "Best Deals This Week" grid, and a Shop by Brand row
- "Trending Now" with four buyer-psychology angles (trending / most gifted / blind-buy safe / compliment-getters)
- Product-type shortcuts, a free-shipping progress incentive, an authenticity section, and a final CTA

### Prototype tools (the floating **PROTO** button, bottom-right)

This concept ships with a built-in review layer:

- **Device preview** — toggle between desktop and a mobile (iPhone) frame
- **A/B annotations** — numbered callouts explaining the CRO rationale behind each section
- **Metrics panel** — the KPIs this layout is designed to move (illustrative data)

These are prototype scaffolding, not part of the storefront design itself.

## Design system

- **Palette:** warm espresso ink + warm white, with gold-leaf and cognac accents; brick-red is reserved for deal markers.
- **Type:** Bodoni Moda (display serif), Archivo (UI sans), and Space Mono (labels) — all Google Fonts, loaded via CDN.

## Deploy with GitHub Pages

1. Create a new repository and upload `index.html` (and this `README.md`).
2. Go to **Settings → Pages**.
3. Set the source to your `main` branch and save.
4. Your page goes live at `https://<your-username>.github.io/<repo>/`.

Any other static host works too (Netlify, Cloudflare Pages, Vercel, etc.) — just upload `index.html`.

## Notes

- Vanilla HTML, CSS, and JavaScript in a single file. The product grid and trending tabs are rendered client-side.
- Product imagery is hotlinked from FragranceBuy's CDN, so an internet connection is needed to display the photos. For a fully durable copy, download the images and swap the `<img>` sources to local files.
