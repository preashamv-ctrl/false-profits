# false-profits

FALSE PROFITS is the Grace in Motion storefront, live at [graceinmotionhq.com](https://graceinmotionhq.com). This repository is the working source of truth for that site.

## File layout

- `index.html` — single-file Tailwind storefront
- `assets/` — product and hero images, referenced with relative paths from `index.html`
- `brand/README.md` — brand kit (palette, typography, voice)

## Production

Production is served by an `nginx:alpine` container on the owner's homelab, behind a Cloudflare tunnel.
