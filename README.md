# Royal Agar Attar: "another one" site

Single static page, no build step. Layout and motion follow the F1 driver-site prompt (loader, cursor liquid reveal, sticky stacking sections, chequered seams, lap trace, timeline rail, contour footer), with Royal Agar Attar content.

- `index.html`: the whole page (styles and scripts inline).
- `assets/js/lenis.mjs`: smooth scroll (self-hosted).
- `assets/img/smoke.webp`: hero background. Free photo by Thomas Stephan on Unsplash (Unsplash License), credited in the footer.
- `assets/img/bottle.webp`: the hero bottle, with "Pure" removed from the label.
- `assets/img/steps/`: frames taken from the real process videos.
- `assets/img/filtering.webp`: real frame, oil filtering.

## Claim rules (keep when editing copy)
- No "pure", "100% pure", "certified", "lab tested" or "organic" until there is a lab report.
- No shipping or export claims until export permits are in place.
- Wood is bought from growers; do not say "we grow our own trees".
- Say "nothing added after distillation".

## Tracking
Every WhatsApp link pushes `whatsapp_click` and `generate_lead` to `dataLayer` with a `wa_location`. Paste a GTM snippet at the marked spot in `<head>`.

## Hosting
Static files; `netlify.toml` publishes the repo root. Works on Netlify, Cloudflare Pages, GitHub Pages or Vercel.
