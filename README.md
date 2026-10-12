# ClearPage

Website for **ClearPage**, a small store selling printable PDF organizers. The first product is **The Elder Care Command Binder**, a 31-page printable organizer for medications, appointments, contacts, legal papers and daily care, sold in A4 and US Letter editions.

Live site: https://clearpage.online

## About this site

A simple static website with no build step and no dependencies. It is hosted on GitHub Pages, and checkout and payments are handled by [Creem](https://www.creem.io).

## Files

| File / folder | Purpose |
|---|---|
| `index.html` | Store page: product preview, FAQ, prices and buy buttons |
| `terms.html` | Terms of Service, license and refund policy |
| `privacy.html` | Privacy Policy |
| `assets/` | Cover images and page previews used on the store page |
| `CNAME` | Custom domain setting for GitHub Pages (do not delete) |

## Updating the store

Prices and checkout links are set in one place, the `STORE` object near the bottom of `index.html`:

```js
const STORE = {
  a4:     { url: "https://www.creem.io/payment/...", price: "$5.99" },
  letter: { url: "https://www.creem.io/payment/...", price: "$5.99" }
};
```

If you change a price, also update the visible price text next to the buy buttons in the "Choose your paper size" section of `index.html`, and keep it in sync with the price in Creem.

## Deploying

Commit changes to the main branch. GitHub Pages rebuilds automatically, usually within a minute or two.

## Contact

Support: support@clearpage.online

## License

All content, layout and design are © 2026 ClearPage. All rights reserved. The product files are licensed for personal, non-commercial use only. See [terms.html](terms.html) for details.
