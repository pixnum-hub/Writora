# Writora PWA — Deployment Guide
## © Manik Roy 2026. All Rights Reserved.

## Files included:
- index.html (rename article-writer.html → index.html)
- manifest.json
- sw.js
- icon-72x72.png
- icon-96x96.png
- icon-128x128.png
- icon-144x144.png
- icon-152x152.png
- icon-192x192.png
- icon-384x384.png
- icon-512x512.png
- apple-touch-icon.png
- favicon-32x32.png
- favicon-16x16.png

## Deployment Steps:
1. Rename article-writer.html to index.html
2. Upload ALL files to the same folder on your web server
3. Serve over HTTPS (required for PWA / Service Worker)
4. Visit your URL — browser will show "Install Writora" prompt

## Recommended hosting:
- GitHub Pages (free)
- Netlify (free)
- Vercel (free)
- Firebase Hosting (free tier)

## Requirements:
- HTTPS is mandatory for Service Workers
- All files must be in the same directory
