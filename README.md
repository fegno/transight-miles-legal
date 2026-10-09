# Transight Miles — legal pages

Static site (plain HTML/CSS, no build) with the Privacy Policy and Delete Account pages shared by
the App Store and Google Play listings of Transight Miles.

| Page | Path |
|---|---|
| Home | `/` |
| Privacy Policy | `/privacy-policy/` |
| Delete Account | `/delete-account/` |

## Use in the stores

- **App Store Connect:** Privacy Policy URL → `/privacy-policy/`.
- **Google Play Console:** Privacy policy → `/privacy-policy/`; Data safety → Account deletion URL → `/delete-account/`.

Both URLs must be public, so host the site (GitHub Pages: Settings → Pages → deploy from `main`
/ root, which needs a public repo or a paid plan; or any static host, Netlify, Vercel, Cloudflare Pages).

## Edit

Edit the HTML files directly; styles are in `style.css`. Keep the effective date and the contact
email (`support@transightmiles.com`) in sync with the app (`src/app/profile/delete-account.tsx`).
The text is a draft based on what the app does; have it reviewed by legal before publishing.
