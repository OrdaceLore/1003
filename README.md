# Efficient System

A lightweight bilingual-ready landing page for [1003.efficientsystem.org](https://1003.efficientsystem.org/). The site is plain HTML and CSS, with no build step or runtime dependencies.

## Deploy to Cloudflare Pages

1. Create a Pages project connected to this GitHub repository.
2. Set the production branch to `main`; leave the build command empty and set the build output directory to `/`.
3. Add `1003.efficientsystem.org` under the Pages project's Custom domains.
4. Cloudflare will create or request the DNS record for the hostname. Confirm DNS is managed by the Cloudflare zone for `efficientsystem.org`.

The page uses Google Fonts as an optional enhancement; system sans-serif fallbacks are included.
