# Bulli Abbai Kodi Pulav website

A static website. No build step, no database, no JavaScript.

## What is inside

- `index.html`: the whole website on one page: hero, our dishes, menu, combos, Swiggy and Zomato buttons, address, phone, hours, Google Maps link, Terms and conditions and Privacy policy
- `404.html`: page not found
- `assets/`: stylesheet, logo, dish photos, hero photo, app icons
- `favicon.ico`, `favicon-16.png`, `favicon-32.png`, `apple-touch-icon.png`, `site.webmanifest`: site icon files made from the restaurant logo
- `_headers`: security and caching headers (used by Cloudflare Pages and Netlify)
- `robots.txt`: search engine crawling rules

## Put it online with a custom domain

1. Buy a domain from any registrar (for example a .in or .com name).
2. Upload this folder to a static host. Cloudflare Pages and Netlify both have a free plan and a "drag and drop a folder" option. Both read `_headers` and `404.html`.
3. In the host's dashboard, add your domain under "Custom domains" and add the DNS records it shows you at your registrar. HTTPS is issued automatically.
4. Open the site on a phone and check both order buttons, the call button, the map link and the Terms and Privacy sections at the bottom.

## Keep in mind

- Menu prices are copied from the printed menu. Swiggy and Zomato show their own prices, and the site says so.
- The hero background photo is a stock image the client supplied; confirm its licence covers commercial use on a public restaurant website before launch.
- The Swiggy and Zomato buttons open the restaurant's page on each app. If either listing changes its URL, update the links in `index.html`.
- The phone number and hours were sourced from third-party listings, not confirmed directly with the restaurant. Double check both before launch.
