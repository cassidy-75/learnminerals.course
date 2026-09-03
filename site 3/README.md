# Learn Minerals — Landman Course Funnel

Static site. No build step, no dependencies.

## Pages
- `index.html` — landing / VSL page. All three CTAs point at the Stripe payment link.
- `welcome.html` — post-purchase welcome page with the GHL booking embed.

## Before going live
1. Set Stripe's success URL to `https://<domain>/welcome`.
2. Replace `REPLACE_WITH_CALENDAR_ID` in `welcome.html` with the GHL booking widget URL.
3. Replace the three `href="#"` resource links in `welcome.html` (course login, field guide PDF, FAQ videos).

## Deploy
Vercel: import the repo, framework preset **Other**, no build command, output directory `.`
