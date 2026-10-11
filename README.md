# SpareQuote

A responsive landing page for SpareQuote, a spare-parts discovery and supplier quote-request project. Includes a starter privacy policy and GitHub Pages deployment workflow.

## Files
- `index.html` — landing page
- `styles.css` — responsive styling
- `privacy.html` — privacy policy starter
- `.github/workflows/pages.yml` — deploys the site to GitHub Pages when changes are pushed to `main`
- `assets/favicon.svg` — site icon

## Before publishing
1. Replace every `CONTACT_EMAIL_PLACEHOLDER` in `index.html` and `privacy.html` with a monitored contact email.
2. Review `privacy.html` against the actual product architecture, data flows, suppliers, hosting, analytics, retention periods, and applicable law. This starter is not legal advice.
3. Check the marketing text against features that are actually available. The copy describes intended workflows and does not claim a working quote platform already exists.
4. Add a license only after deciding how the source code may be reused. A private repository does not need a public open-source license.

## Deploy with GitHub Pages
1. Push these files to the `main` branch.
2. In repository **Settings → Pages**, set the source to **GitHub Actions**.
3. Review the Actions run for its deployment URL.
4. If the repository is private, verify that your GitHub plan and account policy support GitHub Pages for private repositories. The published site itself is public to visitors; repository privacy does not make the website private.

## Local preview
Open `index.html` in a browser. No build step or package installation is required.
