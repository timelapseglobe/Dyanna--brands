# Dyaana Brands Storefront

A responsive full-store skeleton for Dyaana Brands, including:

**Customer contact:** dyaanabrands@gmail.com

- Women-first black-and-white fashion catalogue
- Jewellery collection
- Relove premium pre-owned occasion wear
- Editorial collection gateways and numbered original-media slots
- Category filters, quick view, saved pieces and preview shopping bag
- Relove seller eligibility form
- Mobile navigation and accessible responsive layout

## Media ownership policy

This package intentionally contains **no third-party or generated fashion/product imagery**. It uses only the Dyaana logo supplied by the brand owner. Product and Relove areas remain as designed placeholders until Dyaana's original photographs are ready.

Add only media that Dyaana created, commissioned with written commercial rights, or licensed specifically for commercial website use. Keep photographer/model releases and licence records with the business files.

Recommended folders for future GitHub media:

- `assets/products/` — original new-clothing and jewellery photographs
- `assets/relove/` — original photographs captured after inspection
- `assets/videos/` — compressed product and campaign videos

Use lowercase filenames without spaces, for example `noir-midi-dress-front.webp` and `noir-midi-dress-video.mp4`.

## Preview locally

Open `index.html` in a browser. No installation or build command is required. JavaScript must remain enabled for catalogue filters, quick view, saved pieces and the preview bag.

## Add original product media later

1. Place Dyaana-owned WebP files in `assets/products/`.
2. Open `script.js` and find the corresponding item in the `products` list.
3. Change its empty `image` value to the file path. Example:

   `image: "assets/products/noir-midi-dress-front.webp"`

The product card and quick view will automatically use the image. Until then, the numbered media-reserved design remains visible.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload every file and the `assets` folder from this project. Do not omit `script.js`.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will display the public website link after deployment.

## Connect the original domain later

When the domain is ready, enter it under **Settings → Pages → Custom domain**. GitHub will provide the DNS records to add at the domain provider. After the domain is verified, enable **Enforce HTTPS**.

## Before accepting real orders

Replace the preview catalogue with approved inventory and connect:

- Payment gateway and production checkout
- Shipping/courier service
- Order database or ecommerce backend
- Final customer-support details
- Legal, privacy, shipping, return and Relove policies
- Real Relove image uploads and seller notifications

Product names and prices in this prototype are illustrative. Replace them only after supplier approval.
