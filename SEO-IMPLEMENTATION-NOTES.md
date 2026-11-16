# Dino One Coffee — SEO revision

## Scope
This revision keeps the existing homepage and its working order flows, pricing tables, wedding calculator, regular order form, WhatsApp number, and Cloudflare Workers deployment configuration.

## Changes
- Updated homepage title, meta description, canonical, Open Graph, and Twitter metadata.
- Removed duplicate Open Graph image declaration.
- Expanded Organization and WebSite JSON-LD without publishing a private street address.
- Added dedicated landing pages:
  - `/wedding-coffee-catering/`
  - `/kopi-botolan/`
  - `/sunda-gayo-signature-blend/`
- Added page-specific metadata, WebPage schema, BreadcrumbList schema, and Wedding FAQ/Service schema.
- Updated `robots.txt` and `sitemap.xml` for the four canonical URLs.
- Added WebP derivatives for key images while retaining original images as fallback.
- Added internal links between the homepage and SEO landing pages.
- Preserved `wrangler.jsonc` and the existing root static-assets setup.

## Deploy
1. Download and unzip this archive.
2. Review the files and replace the repository contents with this revised project, or upload only the changed/new files while preserving existing repository settings.
3. Commit to GitHub branch `main`.
4. Wait for Cloudflare Workers Builds to finish successfully.
5. Test:
   - `https://dinoonecoffee.weddingcatering.workers.dev/`
   - `https://dinoonecoffee.weddingcatering.workers.dev/wedding-coffee-catering/`
   - `https://dinoonecoffee.weddingcatering.workers.dev/kopi-botolan/`
   - `https://dinoonecoffee.weddingcatering.workers.dev/sunda-gayo-signature-blend/`
   - `https://dinoonecoffee.weddingcatering.workers.dev/sitemap.xml`
   - `https://dinoonecoffee.weddingcatering.workers.dev/robots.txt`
6. Verify the wedding calculator, regular order form, and WhatsApp message handoff on the homepage.

## Google Search Console
After deployment:
1. Add or verify the URL-prefix property `https://dinoonecoffee.weddingcatering.workers.dev/`.
2. Submit `https://dinoonecoffee.weddingcatering.workers.dev/sitemap.xml`.
3. Use URL Inspection for the homepage and three landing pages.
4. Request indexing after confirming each URL loads correctly.
5. Monitor indexing, impressions, clicks, CTR, and queries.

## Important
- The revision does not register or configure a Google Business Profile.
- No home address is published.
- Search ranking or indexing is not guaranteed.
- The existing regular product prices and wedding package prices were retained from the uploaded source.
