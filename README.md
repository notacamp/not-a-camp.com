# Not A Camp — studio site

The marketing site for **Not A Camp**, an independent software studio.
Static HTML + CSS, no build step.

## Develop

Open `index.html` directly, or serve locally:

```sh
python3 -m http.server 8080
# → http://localhost:8080
```

## Structure

```
index.html      # the page
styles.css      # styles + @font-face
favicon.svg
assets/fonts/   # self-hosted woff2 — DM Sans (body) + DM Mono (wordmark/labels)
assets/logos/   # product marks (Campbooks, Ragomotive, Siccal)
CNAME           # custom domain for GitHub Pages
```

## Fonts

- **DM Sans** — body & headings — SIL Open Font License
- **DM Mono** — wordmark, eyebrows, meta — SIL Open Font License

## Hosting

Served at **not-a-camp.com** (see `CNAME`). Deploy to any static host —
GitHub Pages, Cloudflare Pages, or Netlify all work with zero config.

## License

See `LICENSE`.
