# KAFFA — Cinematic Coffee Brand Site

A moody, filmic coffee-house site in the style of the cinematic AI-website promos: near-black palette, letterboxed hero, animated film grain, a slow-zoom hero photograph and elegant serif type. Built to be the sharpest-looking demo of the set.

## What's inside
- **Cinematic hero** — full-screen coffee pour photo with a 26-second slow zoom (Ken Burns), scroll parallax, letterbox bars and an animated film-grain overlay across the whole site.
- **Marquee band** — an infinite scrolling serif tagline strip.
- **Story section** — brand narrative with a stat row (farms, batch size, rest days, roast count).
- **The Craft** — two moody photo panels plus 4 interactive process steps (Source / Roast / Rest / Pour): click a step to expand its detail.
- **Menu with working order tray** — 6 signature drinks rendered from a data array, filterable by Hot / Cold / Signature. "Add to Order" builds a live order: a floating tray shows drink count and running total, with Clear and Place Order (which confirms on-screen).
- **"Slow Roast Guide" email capture** — the guide offer with a 4-point contents list, email validation and a personalised success state.
- Visit/hours section, scroll reveals, fully responsive.

## Customise it for a buyer
- **Menu:** edit the `MENU` array in the `<script>` (name, category, price, image, description) — cards, filters and the order tray all update automatically.
- **Photos:** replace files in `images/` — `hero.jpg` is the money shot; menu thumbs are `menu-*.jpg`.
- **Guide offer:** headline, bullet list and success copy live in the Guide section; the form is front-end only, so wire the submit handler to the buyer's email platform (Mailchimp, ConvertKit, etc.) when going live.
- **Branding:** rename `KAFFA` in the logo/footer, swap the `--acc` caramel variable for the buyer's colour.

## Tech
Single self-contained `index.html` (embedded CSS + vanilla JS), local images only, no build step, no external requests. Works on any static host (GitHub Pages, Netlify, Vercel).

Photos: Unsplash (free to use). Demo content — menu, prices and hours are illustrative.
