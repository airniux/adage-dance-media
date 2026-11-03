# Adage Dance Media — website

Static one-page site. No build step.

## Deploy (Cloudflare Pages)
1. Cloudflare dashboard → Workers & Pages → Create → Pages → connect this repo (or Direct Upload this folder).
2. Build command: *(none)* · Output directory: `/` (root).
3. Custom domains: add `adagedancemedia.com` and `www.adagedancemedia.com`. Add `adage.dance` as a redirect to the .com (Rules → Redirect Rules).

## Contact form
Uses Web3Forms. Get a free access key at https://web3forms.com (enter hello@adagedancemedia.com; the key is emailed to you),
The key is already set in `index.html` (it is safe to be public).

## Files
- `index.html` — the site
- `media/` — photos (web-sized), `adage-reel.mp4`, `adage-reel-poster.jpg`
- `favicon.svg`, `robots.txt`, `sitemap.xml`, `_headers`, `_redirects`
