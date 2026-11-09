# Still Waters

A quiet, glowing diary for the heart. Installable PWA, works offline.

## Deploy to Netlify (from GitHub)
1. In Netlify: **Add new site → Import an existing project → GitHub**, pick this repo.
2. Leave the build command empty. Publish directory is `.` (already set in `netlify.toml`).
3. Every push to `main` redeploys automatically.

## Updating
Edit files, commit, push. The service worker checks for a fresh page on each visit, so installed copies update on their next open.

## Install on your devices
- **iPhone/iPad (Safari):** Share → Add to Home Screen
- **Android (Chrome):** menu ⋮ → Install app
- **Mac/PC (Chrome or Edge):** install icon in the address bar

## Your entries
Entries are stored privately on each device (never on Netlify).
To move them: Past entries → Save backup, then Load backup on the other device.
