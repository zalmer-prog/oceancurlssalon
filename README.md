# Ocean Curls Salon

Marketing website for **Ocean Curls Salon** — a coastal, women-led hair & beauty salon.
"A group of women loving what we do." ⭐

- **Live site:** https://oceancurlssalon.com
- **Instagram:** [@ocean__curls_salon](https://www.instagram.com/ocean__curls_salon/)

## Stack

Plain static site — `index.html`, `styles.css`, `script.js`. No build step.
Fonts from Google Fonts; gallery/hero imagery from Unsplash (swap in the salon's own photos in `assets/`).

## Local preview

```bash
python3 -m http.server 4177
# then open http://localhost:4177
```

## Deploy

Hosted on Cloudflare Pages (direct upload via wrangler). Pushing to GitHub does **not**
auto-deploy — run the deploy script to publish.

## Editing the important bits

Placeholders to replace with real salon details (all in `index.html`, `#visit` section):

- Phone number (`tel:` links and the displayed number)
- Street address / city / ZIP
- Business hours (currently Tue–Sat sample hours)
- Service pricing (in the `#services` cards) if you want exact numbers
