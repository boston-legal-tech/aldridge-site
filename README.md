# Aldridge Counsel — Website

Static marketing site for Aldridge Counsel, a Boston boutique law firm.

## Local preview

From the project root:

	python3 -m http.server 8000

Then visit `http://localhost:8000/`.

## Pages

- `index.html` — single-page site with hero, about, practice areas, attorneys, contact
- `privacy.html` — privacy policy
- `terms.html` — terms of use
- `404.html` — custom not-found page (wire up `error_page 404 /404.html;` or equivalent on the server)

## Assets

- `images/og-image.png` — Open Graph card (1200×630)
- `favicon.ico`, `apple-touch-icon.png`
- `robots.txt`, `sitemap.xml`
