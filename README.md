# Soundboard Pro

An installable soundboard with tabs, favorites, recording, and a DJ-desk background.

## Put it online (GitHub Pages)
1. On github.com, click **+ > New repository**. Name it (for example `soundboard`) and set it to **Public**.
2. Click **uploading an existing file**, drag in **everything inside this folder** (index.html, manifest.webmanifest, sw.js, both icon files, and starter-sounds.json if you have one), then **Commit changes**.
3. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, pick **main** and **/ (root)**, then **Save**.
4. After a minute or two your link appears at the top of that page: `https://YOUR-USERNAME.github.io/soundboard/`

Email that link. Whoever opens it can install it as an app.

## Installing it
- **Chrome or Edge (computer):** click the **Install app** button in the app, or the install icon at the right end of the address bar.
- **Android (Chrome):** menu, then **Install app**.
- **iPhone/iPad (Safari):** Share button, then **Add to Home Screen**.

## Sending your own sounds with it
Sounds live in each person's browser, so they are not shared automatically. To ship yours:
1. Open the app in the browser where your sounds are, click **Export**, and save `starter-sounds.json`.
2. Upload that file to the repository next to index.html.
3. Anyone opening the link for the first time gets those sounds, tabs, and favorites loaded for them.

Keep `starter-sounds.json` under about 25 MB (GitHub's web upload limit).
