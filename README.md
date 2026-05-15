# Mathieu Prefab Website with Admin Control Panel

This package contains the Mathieu Konstruct Solutions website plus a static admin panel.

## Included
- `index.html` — public website
- `admin.html` — admin login and content editor
- `assets/js/site-data.js` — default site content and localStorage helpers
- `assets/js/main.js` — website rendering and interactions
- `assets/js/admin.js` — admin logic
- `assets/css/style.css` — website styling
- `assets/css/admin.css` — admin styling
- `assets/images/logo.png` — uploaded PNG logo

## Demo Admin Login
- Username: `admin`
- Password: `mks2026`

## How it works
The admin panel stores content in `localStorage`, so it works on GitHub Pages without a backend.

## Publish on GitHub Pages
1. Upload the full folder contents to a GitHub repository.
2. Go to **Settings > Pages**.
3. Set the source branch to `main` and root to `/`.
4. Save and wait for deployment.

## Notes
- This is a static demo admin panel and not real secure server-side authentication.
- Export/import JSON backups are available from `admin.html`.
