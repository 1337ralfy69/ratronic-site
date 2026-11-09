# ratronic.com

Static site, served by GitHub Pages at https://ratronic.com (CNAME file).

- `/` (`index.html`): coming-soon page.
- `/dev-test/` (`dev-test/index.html`, `dev-test/docs.html`): the full product page and docs, not indexed by search engines. Shares `assets/` and `docs/` with the root.

Deploy: push to `main`. In the repo settings, Pages -> Source: Deploy from branch `main`, folder `/ (root)`, custom domain `ratronic.com`, enforce HTTPS.

Buy buttons: the Stripe Payment Links are in `dev-test/index.html`. If a Payment Link redirects to `https://ratronic.com/?paid=1` after checkout, point it at `https://ratronic.com/dev-test/?paid=1` while the coming-soon page is live.
