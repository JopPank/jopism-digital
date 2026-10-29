# Jopism Digital

A standalone French-language landing page for Jopism's digital services.

## Preview

Open `index.html` in a browser. Tailwind CSS is loaded from its CDN; there is
no build step.

## Hosting

Deploy the contents of this folder from the `main` branch of a standalone
GitHub Pages repository. The included workflow deploys the site, and `CNAME`
sets its custom domain to `digital.jopism.com`.

In the domain's DNS settings, add a CNAME record with host `digital` and
target `joppank.github.io`. Configure `digital.jopism.com` as the custom
domain in that repository's **Settings → Pages**. Keep the existing root
domain and `www` records unchanged.
