# RESOLVED Exercise Physiology & Performance: website

Plain HTML, CSS and JS. No build tools. Deploy by dragging the zip (files at the zip root) into Netlify > Deploys.

## Structure
- `index.html` plus one `<slug>/index.html` per page (clean URLs). Blog: `/blog/` and `/blog/<post>/`.
- `assets/` style.css, main.js, brand (logos, favicons, og-image), charts, fonts, team photos.
- `sitemap.xml`, `robots.txt`, `404.html`, `_redirects`, `netlify.toml` (security headers), `favicon.ico`.

## Forms (Netlify Forms)
`/contact/` (form `contact`) and `/referrers/` (form `referral`) post to Netlify and redirect to `/contact/thanks/` and `/referrers/thanks/`. After the first deploy, open Netlify > Forms > Form notifications and add an email notification so submissions reach cameron@resolved-ep.com.au.

## Old domain redirects
`_redirects` sends hydeaep.com.au (and /blogs) to the new site. This only works once `hydeaep.com.au` and `www.hydeaep.com.au` are added as domain aliases on this Netlify site.

## Brand
Black, white, charcoal #1E1E1E, accent blue #68BEE9. Anton + Inter, self-hosted. Logos in `assets/brand/`.

## Open items (shown on the site as "INFORMATION REQUIRED")
Search the HTML for `INFORMATION REQUIRED`: running coaching fees, GLP-1 targets, longevity program relationship, Privacy and Terms legal review.
