# RG Tech Solutions

Marketing website for RG Tech Solutions — an IT consulting and managed services company.
Static HTML/CSS/JS, no build step required.

## Structure

```
index.html          Home
services.html        Services
about.html            About
contact.html          Contact
css/style.css         Shared styles
js/script.js          Nav toggle + small behaviors
assets/favicon.svg    Site icon
.github/workflows/    GitHub Pages deployment workflow
```

## Local preview

Open `index.html` directly in a browser, or serve the folder locally:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deployment

This repo deploys automatically to GitHub Pages via GitHub Actions on every push to `main`
(see `.github/workflows/deploy.yml`). In the repo's **Settings → Pages**, set the source to
**GitHub Actions** (only needs to be done once).

## Editing content

All content (copy, contact details, hours) lives directly in the HTML files — there is no CMS
or backend. Update the placeholder email, phone number, and social links in each page's footer
and contact section before going live.
