# Agent Memory Sprint — Landing Page

Single-page landing page for the Agent Memory Sprint service.

**Live:** Deploy via GitHub Pages (push to `main`, enable Pages in repo settings, source: root).

## Before going live

1. Replace the two Stripe placeholder links:
   ```
   https://buy.stripe.com/PLACEHOLDER
   ```
   Search for `PLACEHOLDER` in `index.html` — there are two CTAs.

2. Update the email address in the final CTA section if needed (`hello@spirittree.dev`).

3. Update OG image URL once you have a real one (`og-image.png`).

4. Update canonical URL if deploying to a custom domain.

## Preview locally

```bash
# Any of these work:
open index.html
npx serve .
python3 -m http.server 8080
```

## Stack

- Single `index.html` — no build step
- TailwindCSS via CDN
- Google Fonts (Inter + JetBrains Mono)
- No dependencies, no node_modules
