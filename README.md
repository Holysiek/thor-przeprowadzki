# THOR Przeprowadzki

Static website for https://thor-przeprowadzki.pl, hosted on Netlify.

[![Netlify Status](https://api.netlify.com/api/v1/badges/a4870307-3293-414e-aa7a-17213bc16383/deploy-status)](https://app.netlify.com/projects/thor-przeprowadzki/deploys)

## Publishing

This repository is linked to the existing `thor-przeprowadzki` Netlify project
(site ID `a4870307-3293-414e-aa7a-17213bc16383`). The production branch is
`main`. Netlify automatically publishes each push. This connection was configured
on 2026-11-06; the first Git-based production deploy published commit `c5a73bd`.
The root `netlify.toml` configures the publish directory as `public`; no build
command is needed. GitHub Pages and a GitHub Actions deployment are not needed.

Edit the site files inside `public/`. Images belong in `public/img/`.
Only `public/` is published, so repository notes are kept off the website.

The contact form uses Netlify Forms (`kontakt`) and the `bot-field` honeypot.
Its successful submission destination is `/dziekujemy`. Keep the existing
Netlify project's form detection, notification settings, and custom domain.

The website files were recovered from the live Netlify deployment on
2026-11-06. The homepage, contact page, and image directory now match the
live site's structure. Long em dashes have been replaced in website copy.
