# ClearGate Hero

Static ClearGate hero page for Cloudflare Pages.

Live site: https://cleargate-hero.pages.dev/

- `public/index.html`: page markup, styles, menu interaction, and a one-time entrance sequence that respects reduced-motion settings
- `public/assets/`: extracted WebP image and WOFF2 fonts

Deploy with `npx --yes wrangler@latest pages deploy public --project-name cleargate-hero --branch main`.
