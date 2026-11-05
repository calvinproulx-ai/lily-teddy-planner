# Lily & Teddy Planner

Phone-friendly nanny checklist and weekly plan. The page lives here on GitHub Pages; the data lives in a private Google Sheet (via Google Apps Script). No data is stored in this repo.

## Files
- `index.html` – the planner page (Today, Week plan, Past days, Ideas)
- `config.js` – the Google Apps Script web app URL (the only setting)
- `.nojekyll` – tells GitHub Pages to serve files as-is

## Updating
Replace `index.html` with a new version. Leave `config.js` alone unless the Apps Script URL changes.
The Google side (`Code.gs`) lives in the sheet: Extensions → Apps Script. After changing it, use
Deploy → Manage deployments → Edit → Version: New version, so the URL stays the same.
