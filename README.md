# StarVault OrbitLink Demo (public)

Synthetic supply-chain analytics demo and offline product catalog.

**Not affiliated with SpaceX, Starlink, or any real company.** All data is synthetic / illustrative.

## Live site

After GitHub Pages is enabled (Deploy from branch → `main` → `/ (root)`):

- Product catalog (site root): `https://satyavathi-gunturi.github.io/starvault-orbitlink-demo/`
- Analytics dashboard: `https://satyavathi-gunturi.github.io/starvault-orbitlink-demo/analytics/`
- Same catalog (older path): `https://satyavathi-gunturi.github.io/starvault-orbitlink-demo/storefront/`

## Contents

| Path | Description |
|------|-------------|
| `index.html` | Offline product catalog at the site root (176 fictional SKUs, search/filters, localStorage demo cart; checkout disabled) |
| `assets/*.webp` | Ten conceptual category images for the root catalog |
| `analytics/index.html` | Self-contained static analytics dashboard (aggregated cubes only; no raw 1M fact rows) |
| `storefront/index.html` | Same offline catalog, so `/storefront/` links keep working |
| `storefront/assets/*.webp` | Same category images for the `/storefront/` copy |
| `storefront/preview.png` | Optional light-theme screenshot |

## What is excluded

- Raw CSV / SQLite / local vault documents
- Real contact details, secrets, API keys
- Live Node checkout server / payment processing
- Real product photography (images are conceptual category plates; SVG fallback if an image fails)

## License / use

Demo and portfolio use only. Do not present as official SpaceX/Starlink materials.
