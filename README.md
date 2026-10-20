# Royal Agar Attar: "another one" site

Single static page, no build step. Layout and motion follow the F1 driver-site prompt (loader, cursor liquid reveal, sticky stacking sections, chequered seams, lap trace, timeline rail, contour footer), with Royal Agar Attar content.

- `index.html`: the whole page (styles and scripts inline).
- `assets/js/lenis.mjs`: smooth scroll (self-hosted).
- `assets/img/smoke.webp`: hero background. Free photo by Thomas Stephan on Unsplash (Unsplash License), credited in the footer.
- `assets/img/bottle.webp`: the hero bottle, with "Pure" removed from the label.
- `assets/img/steps/`: frames taken from the real process videos.
- `assets/img/bottling.webp`: real frame, oil being bottled (grades section).
- `assets/video/harvest-*.{webm,mp4}`: 15s loop cut from the real process footage (wide for desktop, tall for phones), shown as an amber halftone with true colour under the cursor.

## Claim rules (keep when editing copy)
- No "pure", "100% pure", "certified", "lab tested" or "organic" until there is a lab report.
- No shipping or export claims until export permits are in place.
- Wood is bought from growers; do not say "we grow our own trees".
- Say "nothing added after distillation".

## Tracking
Every WhatsApp link pushes `whatsapp_click` and `generate_lead` to `dataLayer` with a `wa_location`. Paste a GTM snippet at the marked spot in `<head>`.

## Hosting
Static files; `netlify.toml` publishes the repo root. Works on Netlify, Cloudflare Pages, GitHub Pages or Vercel.

## main-site/
A full copy of the main website (repo `royal-agar-attar-site`, the design that was live at royalagarattar.qd.je before this F1 design replaced it): page, CSS/JS, all images, the 9 process videos and the render tools. It opens on its own at `/main-site/`. The same old design is also kept in the `backup-old-design` branch of `royal-agar-attar-site`.
