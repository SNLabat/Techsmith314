# Techsmith314

Official one-page website for **Techsmith314** — Twitch Partner, variety streamer, and Dungeon Master of the *Ring and Maker* D&D campaign.

## Features

- Embedded live Twitch stream
- Embedded YouTube playlist for the *Ring and Maker* D&D campaign
- About section with bio and stats
- Links to all social platforms (Twitch, YouTube, Twitter/X, TikTok, Patreon, Bluesky)
- Responsive layout
- Black, orange, and purple color scheme matching the Techsmith314 brand

## Structure

```
index.html   — the entire site (single HTML file, no dependencies)
Logo.png     — Techsmith314 sword logo
```

## Deployment

The site is a single static HTML file with no build step or dependencies.

**Twitch embed:** The embed player automatically detects the current hostname via JavaScript and sets the required `parent` parameter. It works on any domain out of the box.

Deploy to any static host (Vercel, Netlify, GitHub Pages, etc.) by pointing it at the repo root.

## Local Preview

Open `index.html` directly in a browser, or serve it locally:

```bash
npx serve .
```

Note: The Twitch embed requires HTTP (not `file://`) to load. Use a local server for full functionality.
