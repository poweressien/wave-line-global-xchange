# Wave Line Global Xchange

Landing page for **Wave Line Global Xchange** — a currency exchange and cross-border payments service connecting Africa to the world.

## What's inside

A single self-contained `index.html` (logo embedded as base64, no external image assets to manage). Sections:

- Hero with live-style rate board + scrolling rate ticker
- About
- Countries (animated network diagram + send/receive country lists)
- Why Choose Us
- Services
- Trust & Stats (animated counters)
- Testimonials
- Contact (click-to-call, click-to-email, WhatsApp, Facebook, contact form)
- Footer

## Running locally

Just open `index.html` in a browser — no build step, no dependencies.

## Deploying

Works as-is on GitHub Pages, Netlify, Vercel, or any static host. For GitHub Pages:
1. Push this repo to GitHub
2. Repo Settings → Pages → Source: `main` branch, `/ (root)`
3. Site goes live at `https://<username>.github.io/<repo-name>/`

## Contact form

The form is UI-complete but not wired to a backend yet — it currently just shows a success message client-side. To actually receive messages, point it at an endpoint (e.g. a small Django view) and POST the form data there.
