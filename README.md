# Frente & Verso Email Signatures

This folder is ready to be moved into its own GitHub repository.

## Structure

- `signatures/signature-preview.html`
- `signatures/signature-geral.html`
- `assets/logo-frenteverso.png`

## How to use in a dedicated repo

1. Create a new repo and push this `email-signatures` content.
2. Keep the same folder structure (`signatures/` + `assets/`).
3. The signatures in this repo already use a hosted image URL:
   - `https://raw.githubusercontent.com/BWLeoRibeiro/FrenteVerso-email-signatures/main/assets/logo-frenteverso.png`

## Note about Outlook (`cid:` icons)

The social icons use inline SVG for most clients.
There are conditional `cid:` image fallbacks for MS Outlook in both HTML files.
If needed later, we can add hosted PNG fallbacks and remove/replace the `cid:` references.
