# Jupresson GitHub Pages

This repository contains the published static site for Jupresson Portfolio, hosted at https://Jupresson.github.io/.

The site includes:

- a bilingual home page in English and Finnish
- a project gallery with individual project pages
- CV downloads and contact links
- reusable static assets such as images, icons, and PDFs

## How it is updated

The editable source lives in the companion Astro repository, `Jupresson.github.io-src`. That source repo runs the build in GitHub Actions, generates the static `dist/` output, and syncs it into this repository for GitHub Pages to serve.

## Contents

- `index.html` and localized pages for the public site
- project page folders under `Project*Page/`
- static assets such as `FacePicture.webp`, project images, and CV PDFs
- the `ReadMoreToggle.js` script used by the site

If you want to change the site content or structure, edit the source repository rather than this generated output.
