# Nap-Time Marathon

55-week marathon training plan as an iPhone app (PWA). Works offline; your "Done" ticks are saved on the phone.

## Put it online (GitHub Pages)
1. Create a new repository on github.com (e.g. `nap-time-marathon`).
2. Upload everything in this folder (keep the `icons` folder).
3. Repository **Settings → Pages** → Source: **Deploy from a branch**, Branch: **main**, folder **/ (root)** → Save.
4. After a minute your app is at `https://<your-username>.github.io/nap-time-marathon/`.

## Install on iPhone
1. Open the link in **Safari**.
2. Tap **Share → Add to Home Screen → Add**.
3. Open it from the home screen icon.

## Updating later
Change the files, and in `sw.js` change `ntm-v1` to `ntm-v2` (and so on). Open the app twice to load the new version.

Note: ticks are stored in the app on your phone. Deleting the app from the home screen deletes your ticks.
