# Blinkskit GX Promotional Landing Page

A static promotional landing page for the Opera GX desktop browser offer.

## Stack
- HTML
- CSS
- Vanilla JavaScript
- Vercel static hosting

There is no PHP, database, server-side application, or custom postback endpoint.

## Local preview

Open `index.html` in a browser, or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Offer destination

The main CTA links to the supplied CPAGrip sponsor destination. Visitors are told before continuing that they will reach a third-party sponsor page and that the sponsor may request an email address or ZIP/postal code to check eligibility.

This page is independent and is not operated by or affiliated with Opera.

## Vercel deployment

Import this repository into Vercel and use the `main` branch. No framework preset, build command, or output directory is required for this static site. The site root is the repository root.

After the first deployment, add `gx.blinkskit.com` in the Vercel project's **Settings → Domains**. Follow the exact DNS record Vercel displays for the subdomain, then wait for verification and SSL provisioning.

## Files
- `index.html` — page content and sponsor disclosure
- `style.css` — responsive visual design
- `script.js` — accessible mobile navigation
