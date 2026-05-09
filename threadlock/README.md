# Threadlock — Reddit Archiver

Save Reddit threads (post + all comments) locally before they get deleted. No backend, no account needed.

## Features

- Paste any Reddit URL → archives post + all comments instantly
- All data stored in your browser (`localStorage`) — works offline
- Shows deleted/removed comments marked clearly
- Browse all saved threads in the sidebar
- Threaded comment display with depth

## Deploy to Vercel (30 seconds)

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → Import project → select repo
3. No config needed — click Deploy
4. Done ✓

## Local dev

Just open `index.html` in a browser — no build step.

## Notes

- Reddit's API is public for read-only thread JSON — no API key needed
- If a thread is already deleted before you archive it, it may not load
- Archives are stored per-browser; clear browser data = lose archives
- CORS proxies used as fallback if direct fetch is blocked
