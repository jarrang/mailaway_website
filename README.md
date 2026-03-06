# MailAway Website

Static marketing site for [mail-away.co.uk](https://www.mail-away.co.uk).

## Deployment

The site is published via **GitHub Pages** from the `gh-pages` branch, serving from the `docs/` directory.

Custom domain: `mail-away.co.uk` (configured via `docs/CNAME`).

## Structure

```
docs/           ← Published root
├── index.html  ← Main page
├── CNAME       ← Custom domain config
├── css/
│   └── styles.css
└── assets/
    └── images/
```

## Making Changes

Edit the static files in `docs/` directly, then commit and push to the `gh-pages` branch.
