# Paris Croisserie — Bakery & Café

Marketing website for **Paris Croisserie Bakery & Café** in Lubbock, TX.

A single-page, fully responsive static site (one `index.html`, Tailwind via CDN) in a
royal-blue-and-gold Parisian theme. Sections: hero, about, menu, gallery, and visit
(hours, contact, and an embedded map).

## Run locally

It's a static page — just open `index.html`, or serve the folder:

```bash
python -m http.server 5500
# then visit http://localhost:5500
```

## Structure

- `index.html` — the entire site
- `images/` — logo and photography

## Deploy

Any static host works (Netlify, Vercel, GitHub Pages, Cloudflare Pages). `index.html`
is the entry point; no build step required.
