# Portfolio

Static site: `index.html`, `site.css`, `site.js`, `assets/resume.pdf`. No build step, no dependencies.

**Run:** `python3 -m http.server 8080` then open http://localhost:8080
**Deploy:** upload the folder to Netlify, Cloudflare Pages or GitHub Pages. `_headers` works on Netlify and Cloudflare Pages; add the same headers elsewhere.
**Edit content:** projects, skills and essays are the `PROJECTS`, `SKILLS` and `ESSAYS` arrays at the top of `site.js`.

Live: GitHub repository list (public API, cached in the browser for an hour, snapshot fallback).
Curated: everything else (repository names show instantly from a built-in list and are replaced by live data when the API responds), including the case studies (written from cloned source on 26 Oct 2026) and LinkedIn details (not accessible to me; nothing was scraped).
Not included: contact form (no backend), sitemap and canonical URL (domain unknown), social preview image.
