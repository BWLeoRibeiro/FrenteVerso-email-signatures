# Frente & Verso Email Signatures

This folder is ready to be moved into its own GitHub repository.

## Structure

- `signatures/signature-preview.html`
- `signatures/signature-geral.html`
- `assets/logo-frenteverso.png`

## How to use in a dedicated repo

1. Create a new repo and push this `email-signatures` content.
2. Keep the same folder structure (`signatures/` + `assets/`).
3. If you want fully hosted image URLs, replace:
   - `../assets/logo-frenteverso.png`
   with your GitHub raw URL, for example:
   - `https://raw.githubusercontent.com/<org>/<repo>/<branch>/assets/logo-frenteverso.png`

## Note about Outlook (`cid:` icons)

The social icons use inline SVG for most clients.
There are conditional `cid:` image fallbacks for MS Outlook in both HTML files.
If needed later, we can add hosted PNG fallbacks and remove/replace the `cid:` references.
