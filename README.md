# StarVault OrbitLink Demo (public)

Synthetic supply-chain analytics demo and offline product catalog.

**Not affiliated with SpaceX, Starlink, or any real company.** All data is synthetic / illustrative.

## Live site

After GitHub Pages is enabled (Deploy from branch → `main` → `/ (root)`):

- Analytics dashboard: `https://satyavathi-gunturi.github.io/starvault-orbitlink-demo/analytics/`
- Product catalog: `https://satyavathi-gunturi.github.io/starvault-orbitlink-demo/storefront/`

## Contents

| Path | Description |
|------|-------------|
| `analytics/index.html` | Self-contained static analytics dashboard (aggregated cubes only; no raw 1M fact rows) |
| `storefront/index.html` | Offline product catalog (176 fictional SKUs, search/filters, localStorage demo cart; checkout disabled) |
| `storefront/assets/*.webp` | Ten conceptual category images shared by SKUs in each family |
| `storefront/preview.png` | Optional light-theme screenshot |

## What is excluded

- Raw CSV / SQLite / local vault documents
- Real contact details, secrets, API keys
- Live Node checkout server / payment processing
- Real product photography (images are conceptual category plates; SVG fallback if an image fails)

## License / use

Demo and portfolio use only. Do not present as official SpaceX/Starlink materials.
