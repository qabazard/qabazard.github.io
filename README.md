# Hamid Qabazard — Architect

A minimal one-page Jekyll site for an architectural practice based in Kuwait.

## Structure
- `index.html`: Single-page layout with responsive logo and centered contact links.
- `_config.yml`: Site configuration and contact details (email, phone, Instagram).
- `assets/styles.css`: Global styles, dark theme, responsive layout, font setup.
- `Hamid_Qabazard_Logo-02.jpg`: Temporary logo asset (replace with SVG variants when ready).

## Updating contact details
Edit `_config.yml` and update:

```yaml
email: hello@example.com
phone: "+965 5555 5555"
instagram: hamidqabazard
```

## Fonts
The brand font is Gotham (licensed). When ready, add the `.woff2` files to `assets/fonts/` and keep the same filenames used in `assets/styles.css`, or update the `@font-face` sources there. The site will fall back to Montserrat/system fonts until Gotham files are provided.

## GitHub Pages
Pushing to the `main` branch will trigger a rebuild and deploy on GitHub Pages.
