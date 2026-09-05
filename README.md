# bryanfreytes.com

Personal website for Bryan Freytes-Mendez. Static site — plain HTML + CSS, no build step, no frameworks.

## Deploy

This repo is connected to **Cloudflare Pages** (production branch: `main`).
Push to `main` and Cloudflare deploys automatically.

## Structure

```
index.html              Home
about.html              About
projects.html           Projects
experience.html         Experience
formula-calculator.html Baby-formula scoop calculator (pure JS)
404.html                Custom 404
css/styles.css          All styles
assets/favicon.svg      Favicon
images/profile.jpg      Portrait
sitemap.xml             Sitemap
robots.txt              Robots
```

## Notes

- Cloudflare Pages serves `404.html` automatically for unknown paths.
- Cloudflare injects its own analytics beacon at deploy time — do not add one manually.
