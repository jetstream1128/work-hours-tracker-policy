# Ultimate Work Hours Tracker - Legal Pages Repo

This folder is a standalone package for a separate public GitHub repository that hosts legal pages via GitHub Pages.

## Included

- `index.html`
- `privacy-policy/index.html`
- `terms-of-use/index.html`
- `content/PRIVACY_POLICY.md`
- `content/TERMS_OF_USE.md`
- `.github/workflows/deploy-pages.yml`

## How to publish in a separate repo

1. Create a new public GitHub repository (for example: `work-hours-legal`).
2. Copy all files from this folder (`legal-pages-repo/*`) to the root of that repo.
3. Push to `main`.
4. In GitHub: `Settings -> Pages`, set source to `GitHub Actions`.
5. Wait for workflow `Deploy legal pages` to finish.

## Example URLs

If your repo is `https://github.com/<user>/work-hours-legal`, URLs will be:

- `https://<user>.github.io/work-hours-legal/`
- `https://<user>.github.io/work-hours-legal/privacy-policy/`
- `https://<user>.github.io/work-hours-legal/terms-of-use/`

## App integration

In your app Firebase Remote Config set:

- `paywall_privacy_url`
- `paywall_terms_url`

to URLs from the new legal repo.
