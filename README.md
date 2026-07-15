# Horizonical Export Imports — Website

Static website for Horizonical Export Imports (moringa leaf powder & dehydrated fruit/vegetable exporter).

## Structure

- `index.html` — main site (single self-contained file, images embedded)
- `privacy-policy.html` — Privacy Policy & Terms of Use page

No build step, no dependencies, no separate image files — everything needed is inside these two HTML files.

## Local preview

Just open `index.html` directly in a browser, or run a local server:

```
npx serve .
```

## Deployment

This repo is set up to deploy directly on [Vercel](https://vercel.com) as a static site — no configuration needed. Connect the repo in the Vercel dashboard and deploy.

## To-do before going live

- [ ] Replace the Google Analytics placeholder ID (`G-XXXXXXXXXX`) in `index.html` with a real GA4 Measurement ID
- [ ] Verify all product certification claims (USDA Organic / EU Organic / Control Union) are accurate before publishing
- [ ] Have `privacy-policy.html` reviewed by a lawyer
- [ ] Replace placeholder lab specification data in product modals with real Certificates of Analysis
- [ ] Add real photos for the remaining placeholder products (mixed vegetables, banana, papaya)
- [ ] Connect a custom domain (e.g. www.horizonical.com) once hosted on Vercel
