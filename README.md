# Kumo Matcha Bar — website

Technology for Business midterm project (fictional business).

## Files

| File | Purpose |
|---|---|
| `index.html` | The single page: header + navigation, hero (name and value proposition), About, Menu with prices, Contact (call to action, hours, location), footer |
| `style.css` | Colours, fonts, spacing and layout. The `@media` rules at the bottom make it work on phones |
| `images/` | Original SVG illustrations of each drink (every `<img>` has alt text) |

All paths are relative (`images/matcha-latte.svg`), so they work after hosting.

## Publish on GitHub Pages

1. Create a public repository on GitHub, e.g. `kumo-matcha-bar`.
2. Upload everything in this folder (keep `index.html` at the top level, not inside another folder).
3. Repository **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder `/ (root)` → Save.
4. Wait 1–2 minutes. The site appears at `https://<your-username>.github.io/kumo-matcha-bar/`.
5. Open that link in a private/incognito window to check it loads without signing in.
