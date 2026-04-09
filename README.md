# legal-pages

Static legal pages for apps hosted via GitHub Pages on the custom domain `legal.marcelasmar.com`.

## Structure

- `/index.html` - landing page for legal documents
- `/styles.css` - shared styling for all pages
- `/einbuergerungstest/privacy/index.html` - privacy policy for Einbürgerungstest
- `/einbuergerungstest/support/index.html` - support + FAQ for Einbürgerungstest
- `/einbuergerungstest/disclaimer/index.html` - disclaimer/terms for Einbürgerungstest
- `/einbuergerungstest/privacy.html` - backward-compatible redirect to `/einbuergerungstest/privacy/`
- `/einbuergerungstest/support.html` - backward-compatible redirect to `/einbuergerungstest/support/`
- `/einbuergerungstest/disclaimer.html` - backward-compatible redirect to `/einbuergerungstest/disclaimer/`
- `/CNAME` - GitHub Pages custom domain configuration

## Add a new app legal section

1. Create a folder at the repo root for the app slug, for example `/myapp/`.
2. Add at minimum:
   - `/myapp/privacy/index.html`
   - `/myapp/support/index.html`
   - `/myapp/disclaimer/index.html`
3. Reuse `/styles.css` and keep the same top navigation pattern (`Home`, `Privacy`, `Support`, `Disclaimer`).
4. Add links/cards on `/index.html` for the new app pages.
5. Replace TODO placeholders (owner name, support email, policy links, address if needed) before publishing.

## GitHub Pages and custom domain

This project uses GitHub Pages with a custom domain. The `CNAME` file must exist at the repository root and contain exactly:

`legal.marcelasmar.com`
