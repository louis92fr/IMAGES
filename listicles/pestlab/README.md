# PestLab listicles

Three standalone pages for PestLab™ USO, each rebuilt from a reference layout.

| File | Reference layout |
|---|---|
| `7-reasons.html` | godisabove.com "7 reasons" listicle (sticky CTA, review cards, offer card) |
| `special-report.html` | mellowsleep.com "special report" story advertorial |
| `10-reasons.html` | mellowsleep.com "10 reasons" listicle with embedded buy box and countdown |

## Editing
- **Button link:** change `CTA_URL` (or `PRODUCT_URL` in `10-reasons.html`) in the `<script>` at the bottom of each file.
- **Countdown end:** `SALE_END` in `10-reasons.html`.
- **Bundles/prices:** `BUNDLES` in `10-reasons.html` (matches the store: 1 / 3 / 6 / 9 devices).
- **Images** load from PestLab's Shopify CDN, so the files work anywhere.

To use on Shopify: create a page template with a Custom Liquid section and paste the file's `<style>`, body markup and `<script>`, or host the HTML file as-is.

## Preview copies
`preview/` holds self-contained copies of every page with all images embedded, so they show images anywhere (downloaded, in the Claude app, offline). Use the main files (which load images from PestLab's Shopify CDN) for the real site; regenerate the previews after editing a page.
