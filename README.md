# ClearPage

Website for **ClearPage**, a small store selling printable PDF organizers. The first product is **The Elder Care Command Binder**, a 31-page printable organizer for medications, appointments, contacts, legal papers and daily care, sold in A4 and US Letter editions.

Live site: <https://clearpage.online>

## About this site

A simple static website with no build step and no dependencies. It is hosted on GitHub Pages, and checkout and payments are handled by [Creem](https://www.creem.io).

## Files

| File / folder | Purpose |
| --- | --- |
| `index.html` | Home page: product list, caregiver guides, how it works, FAQ |
| `elder-care-command-binder.html` | Product page: preview, who it is for, prices, buy buttons and FAQ |
| `guides/` | Hub page listing all caregiver guides |
| `caregiver-binder-what-to-include/`, `emergency-information-sheet/`, `medication-list-for-elderly-parent/`, `questions-to-ask-your-parents-doctor/`, `hospital-discharge-checklist/` | Free caregiver guides (one `index.html` each) |
| `terms.html`, `privacy.html` | Terms of Service (license and refund policy) and Privacy Policy |
| `404.html` | Page shown for unknown URLs |
| `assets/` | Cover images, page previews, social images and `guide.css` (shared styles for guide pages) |
| `favicon.svg`, `favicon.ico`, `apple-touch-icon.png` | Site icons |
| `sitemap.xml`, `robots.txt` | Search engine files. Add new pages to the sitemap |
| `CNAME` | Custom domain setting for GitHub Pages (do not delete) |

## Adding a guide

Copy an existing folder such as `medication-list-for-elderly-parent/`, edit the text, title, description, canonical URL and structured data, then add the page to `sitemap.xml`, `guides/index.html` and the guide lists on the home and product pages.

## Contact

Support: <support@clearpage.online>

## License

All content, layout and design are © 2026 ClearPage. All rights reserved. The product files are licensed for personal, non-commercial use only. See [terms.html](terms.html) for details.
