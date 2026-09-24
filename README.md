# Save The Puppy

Files: index.html (the game), manifest.webmanifest and sw.js (install as an app), icon-192.png, icon-512.png, og-image.png (share preview).

## Put it online with GitHub Pages
1. On GitHub, create a new public repository named `save-the-puppy`.
2. Upload all files in this folder to the repository root.
3. Open Settings, then Pages. Under Build and deployment choose Deploy from a branch, pick `main` and `/ (root)`, and save.
4. After a minute the game is live at `https://YOUR-USERNAME.github.io/save-the-puppy/`.
5. In index.html, replace `YOUR-USERNAME` (3 places in the head, in the og:url, og:image and twitter:image tags) with your GitHub username, then commit. The share preview needs this.

## Install on a phone
Open the live link in Chrome (Android) and choose Install app, or in Safari (iPhone) choose Share, then Add to Home Screen.

## Updating later
Change `V` in sw.js (for example puppy-v2) whenever you update the game, so players get the new version.
