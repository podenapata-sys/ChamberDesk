# ChamberDesk

Website, online booking and patient accounts for dental clinics in Bangladesh, in one place,
for a small monthly fee. By Future Stack Solutions, Dhaka.

This repository holds the **landing page** used to find the first five pilot clinics. The
platform itself is not built yet. It will grow out of the Omega Dental website and dashboard
(omegadentalbd.com).

## What's here

| Path | What |
|---|---|
| `index.html` | One-page site, Bangla first with an English toggle. No build step and no third-party scripts. |
| `img/` | Screenshots of omegadentalbd.com, shown with the clinic owner's consent (given 2026-11-09). The dashboard image shows invented sample records only. |
| `fonts/` | Noto Sans Bengali, Sora, Inter (SIL Open Font License), self-hosted. |

## Publish with GitHub Pages

Settings → Pages → Build and deployment → Source: **Deploy from a branch** → `main` / `(root)` → Save.
The page goes live at `https://podenapata-sys.github.io/<repo-name>/` within a minute or two.
Add a custom domain on the same screen once it is bought.

## Editing

All text is in `index.html`. Each visible string carries `data-bn` and `data-en`, and the default
Bangla text is also written between the tags, so the page reads without JavaScript. Change all
three together. Prices are in the `#pricing` section. The WhatsApp number is near the bottom, in
the `WA` constant.
