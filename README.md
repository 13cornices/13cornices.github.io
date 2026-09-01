# Soccer Sub Tracker PWA

Upload every file in this folder to the same HTTPS folder on your website.

Open `index.html` on the phone once while online. The service worker caches the app files, icons, and current CDN scripts. After that first successful load, the app should open from cache and continue working offline.

On Android, open the site in Chrome and choose **Install app** or **Add to Home screen**.

On iPhone, open the site in Safari, tap **Share**, then **Add to Home Screen**.

To publish an update, replace the files on the website and change `CACHE_NAME` in `service-worker.js`, for example from `soccer-sub-tracker-v6` to `soccer-sub-tracker-v7`. Phones will pick up the new cache after they open the app online.
