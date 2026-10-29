# BRIXGADGETZ — Ecommerce Website Starter

A responsive React + TypeScript + Vite storefront for smartphones, laptops, headphones, earbuds, chargers, power banks, tablets, wearables and accessories.

## Features
- Home page with phone hero and category sections
- Shop page with search, category filters, price filter and sorting
- Product details and specifications
- Cart with quantity changes and remove controls
- Wishlist saved in local browser storage
- Checkout demo form
- About and contact pages
- Responsive navigation and newsletter UI
- Vercel, Netlify and Cloudflare Pages configuration

## Run locally
1. Install Node.js LTS.
2. Extract the ZIP and open a terminal in the project folder.
3. Run `npm install`
4. Run `npm run dev`

## Build and deploy
Run `npm run build`; output is in `dist/`.
- Vercel: build command `npm run build`, output directory `dist`.
- Cloudflare Pages: build command `npm run build`, output directory `dist`.
- Netlify: configured in `netlify.toml`.

## Brand
BRIXGADGETZ · +1 715 802 0318 · shop@brixgadgetz.com · California, USA

## Before launch
Checkout is a demo and does not process payment, reserve stock or create real orders. Connect a commerce backend such as Shopify or Medusa and a secure payment provider such as Stripe Checkout before selling. Never collect raw card details in this frontend.

Product names, specs, prices and Unsplash images are sample content. Verify image licensing and replace sample product data with your actual stock. Product images have a fallback placeholder if a remote image fails.
