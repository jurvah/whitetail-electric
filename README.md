# Whitetail Electric website

Static site for Whitetail Electric (Columbia Falls, MT), served by GitHub Pages.

- `index.html` — home page
- `contact.html` — quote request form
- `assets/img/` — job photos
- `llms.txt`, `sitemap.xml`, `robots.txt`

## Before launch
- Replace placeholders: `[PHONE]`, `[LICENSE #]`, `[LOGO]`, photo caption, `[Privacy notice]`, response window
- Connect the form: create a Formspree form and replace `[FORM_ID]` in `contact.html`
- Add the Google Maps embed in place of the map placeholders
- Remove the `noindex` meta tags in both pages and restore `robots.txt` (`Allow: /` plus the sitemap line) to let search engines index the site
