# neighborit.net

Website for Neighbor IT, IT support and consulting in Clarksville, Tennessee.

A static site with no build step. Every file in this folder is published as-is.

| File | Purpose |
|---|---|
| `index.html` | The whole site: content, styles and script in one page |
| `404.html` | Page shown for broken links |
| `favicon.svg` | Browser tab icon |
| `robots.txt`, `sitemap.xml` | Help search engines index the site |
| `_headers` | Security headers (used by Cloudflare) |

## Common edits

- **Hours:** the `HOURS` list in the script near the bottom of `index.html` (minutes after midnight, Sunday first), the hours line in the Contact section, and `openingHoursSpecification` in the `<head>`.
- **Phone number:** uncomment the "Call or text" line in the Contact section.
- **Contact form:** replace `WEB3FORMS_ACCESS_KEY` in `index.html` with the key from web3forms.com. Until then, the form asks visitors to email hello@neighborit.net.

## Hosting

Served by Cloudflare from this repository. Pushing to `main` publishes the change within a minute or two.
