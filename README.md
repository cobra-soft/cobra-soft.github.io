# cobraS0FT · Personal Hub

Static personal website with a Material Design 3 / Monet-inspired palette, English / Russian / Ukrainian translations, responsive navigation, light/dark/system mode, and locally saved preferences.

## Deploy on Cloudflare Pages

1. Upload these files to a single GitHub repository (for example `cobra-soft/cobraTest`).
2. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git. Select the repository.
3. Framework preset: None. Build command: leave empty. Build output directory: `.` (repository root).
4. Deploy. Updates to the selected branch deploy automatically.

No API tokens, backend, database, build tools or npm dependencies required. Fonts are loaded from Google Fonts with local fallbacks.

## Customize

- Contact URLs and email: `index.html` and the copy-email handler in `app.js`.
- Project cards: `index.html`; translated descriptions: `app.js`.
- Palette hues: `seeds` in `app.js`; styling: `styles.css`.
- The color palettes are Monet-inspired, not an extraction of the visitor's Android wallpaper.
- The project links currently lead to the channel and the original repository; replace them with direct release URLs when available.

Open `index.html` locally to preview. Clipboard copy is supported on HTTPS or localhost; on other origins the button falls back to opening an email draft.
