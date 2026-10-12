# Plant Care

A free iPhone web app for watering reminders and weather alerts: bring plants inside before cold nights and storms, and put them out when the weather's nice.

## Put it online (free, about 10 minutes)

1. **Make a GitHub account** at github.com if you don't have one.
2. **Create a repository:** click **+** (top right) → **New repository**. Name it `plant-app`, set it to **Public**, and click **Create repository**.
3. **Upload the files:** on the new repo page, click **uploading an existing file**. Drag in all six files (`index.html`, `manifest.webmanifest`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png`; this README is optional). Click **Commit changes**.
4. **Turn on GitHub Pages:** go to **Settings** → **Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, Branch to **main** and folder **/ (root)**, then **Save**.
5. **Wait a minute or two,** then refresh that Settings → Pages screen. It will show your link, like `https://YOUR-USERNAME.github.io/plant-app/`.

## Put it on your iPhone

1. Open your link in **Safari** (it has to be Safari).
2. Tap the **Share** button → **Add to Home Screen** → **Add**.
3. Open it from the new home-screen icon, then set your location and add your plants.

Do your setup from the home-screen icon, not the Safari tab. iPhone keeps the two separate, so plants added in Safari won't appear in the home-screen app.

## Good to know

- **Your data lives on your phone.** Nothing is sent anywhere except your location (to get the forecast). Use **Settings → Export backup** now and then.
- **Weather** comes from Open-Meteo, a free service with no account or key needed. It refreshes when you open the app, at most once an hour (tap ↻ to force it).
- **No push notifications yet.** The app shows what needs doing when you open it. Phone notifications are the next step.
- **Making changes:** upload the changed file to GitHub the same way (it replaces the old one). If your phone keeps showing the old version, change `plantcare-v1` to `plantcare-v2` in `sw.js` and upload that too.
