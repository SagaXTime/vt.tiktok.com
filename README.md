# Location Panel

A lightweight single-file redirect tracker.  
Captures visitor geolocation before redirecting them to any target URL.

## Features

- Geolocation capture (lat, lng, accuracy, timezone, language, screen size, user agent)
- Configurable redirect target, loading text, and delay
- Admin panel via `#admin` hash
- Log viewer with Google Maps links
- CSV export
- No backend required — runs entirely in the browser

## Usage

1. Open `location-panel.html#admin`
2. Set target URL and preferences
3. Save config
4. Share the link without `#admin`
5. Check incoming logs in the admin panel

## Deploy

Upload `location-panel.html` to any static host:
- GitHub Pages
- Vercel
- Netlify

## Note

Logs are stored in `localStorage` of the admin's browser.  
For cross-device logging, a webhook integration is recommended.

## License

MIT
