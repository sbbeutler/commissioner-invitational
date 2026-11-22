# The Commissioner Invitational

A single-page browser game (plain HTML, CSS and JavaScript, no build step).

- Live site: https://tcigolfgame.com
- Hosting: Cloudflare (Workers static assets), deployed automatically from `main`.
- The game lives in `public/` (`public/index.html` and `public/assets/`). Config is in `wrangler.jsonc`.
- The root `index.html` only redirects old GitHub Pages links to the live site.

## Run locally
Open `public/index.html` in a browser.
