# Zia-E-Madni Travel & Tours

Fast, static website built with HTML, CSS, and JavaScript. The complete site is in `index.html`; images, logos, icons, and the testimonial video are in `assets/`. There is no framework, build step, or package installation.

## Deploy with Cloudflare Pages

1. In Cloudflare, choose **Create application** > **Pages** > **Connect to Git**.
2. Select `ziaemadnitravelandtours-boop/zia-e-madni-travel-tours` and the `main` branch.
3. Set **Framework preset** to **None**, leave **Build command** empty, and set **Build output directory** to `.`.
4. Create and deploy. Cloudflare Pages will redeploy when changes are pushed to `main`.

The root `_headers` file sets security-related response headers and cache lifetimes for the site and its assets.

## Editing content

Site content and configuration are in the `window.ZIA_CONFIG` block near the bottom of `index.html`. Keep asset filenames in `assets/` unchanged when replacing media, or update their references in the page.
