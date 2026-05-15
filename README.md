# Atlas Goods

Atlas Goods is a premium headless commerce storefront for outdoor provisions, seasonal product capsules, collection browsing, product detail pages, cart behavior, and checkout handoff.

This website is powered by Wix Headless and built using [wix-headless.dev](https://www.wix-headless.dev).

## Links

- Live site: [https://atlasgoods.store](https://atlasgoods.store)
- Source: [https://github.com/wix-incubator/atlasgoods](https://github.com/wix-incubator/atlasgoods)
- Wix site ID: `f28bf272-b4db-4556-b006-74cb6e37a9d0`

## What It Showcases

- A custom Astro storefront using Wix as the commerce backend.
- Product listing, product detail, collection filtering, and search-style catalog pages.
- Cart and checkout handoff from a bespoke front end.
- SEO metadata on product and collection routes.
- Public `robots.txt` and `llms.txt` configured through Wix SEO txt APIs.
- Deployment with `wix release`.

## Wix Solutions Used

- Wix Headless Site for the managed site/runtime foundation.
- Wix Stores for catalog, products, and product data.
- Wix eCommerce for cart and checkout flows.
- Wix Categories for catalog taxonomy.
- Wix Data for supporting structured records.
- Wix SEO for product and collection SEO tags.
- Wix Redirects for checkout/redirect flows.

## Wix SDKs And Packages

- `@wix/astro`
- `@wix/astro-pages`
- `@wix/sdk`
- `@wix/stores`
- `@wix/ecom`
- `@wix/categories`
- `@wix/data`
- `@wix/seo`
- `@wix/redirects`

## Local Development

Create a local env file from `.env.example` or run the Wix CLI env setup for the connected site.

```bash
npm install
npm run dev
```

## Build And Release

```bash
npm run build
npm run release
```
