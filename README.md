# legal-pages

Static legal pages for apps hosted via GitHub Pages on the custom domain `einbuergerungstest.marcelasmar.com`.

## Structure

- `/index.html` - landing page for legal documents
- `/styles.css` - shared styling for all pages
- `/privacy/index.html` - privacy policy for Einbürgerungstest
- `/support/index.html` - support + FAQ for Einbürgerungstest
- `/disclaimer/index.html` - disclaimer/terms for Einbürgerungstest
- `/app-ads.txt` - app-ads.txt declaration for AdMob verification
- `/CNAME` - GitHub Pages custom domain configuration

## Add a new app legal section

1. Create top-level folders for each legal page:
   - `/privacy/index.html`
   - `/support/index.html`
   - `/disclaimer/index.html`
2. Reuse `/styles.css` and keep the same top navigation pattern (`Home`, `Privacy`, `Support`, `Disclaimer`).
3. Keep all links root-based (`/`, `/privacy/`, `/support/`, `/disclaimer/`).
4. Replace TODO placeholders (version/build numbers and any future missing values) before publishing updates.

## GitHub Pages and custom domain

This project uses GitHub Pages with a custom domain. The `CNAME` file must exist at the repository root and contain exactly:

`einbuergerungstest.marcelasmar.com`
