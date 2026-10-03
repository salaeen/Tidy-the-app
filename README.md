# Tidy

A chore tracker that gives you points. It runs as a web app you add to your iPhone Home Screen, with no App Store and no server. Your data stays on your phone.

## Put it online (free, about 5 minutes)

This is easiest from a computer, but it also works in Safari on the phone.

1. Sign in to [github.com](https://github.com) (or make a free account).
2. Click **New repository**. Name it `tidy`, leave it **Public**, and click **Create repository**.
3. On the empty repository page, click **uploading an existing file**. Drag in every file from this folder (the files, not the folder itself) and click **Commit changes**.
4. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick **main** and **/ (root)**, and click **Save**.
5. Wait a minute or two. Your app is at `https://YOUR-USERNAME.github.io/tidy/`.

The repository has to be public for free GitHub Pages. That only makes the app's code public. Your chores and points never leave your phone.

## Install it on the iPhone

1. Open your `github.io` link in **Safari**.
2. Tap **Share**, then **Add to Home Screen**, then **Add**.
3. Open Tidy from the Home Screen icon from now on.

The Home Screen app keeps its own data, separate from the Safari tab. Anything you log in the Safari tab won't show up in the installed app, so start logging after you install it.

## Keep a backup

Everything is stored on the phone. Deleting the Home Screen icon deletes the data with it. Every few weeks, go to **Settings → Save backup file** and save it to iCloud Drive. **Restore from file** brings it back.

## Change things

- Chores, points, schedules and rewards: edit them in the app (the dots on each row, or **Add a chore**).
- The app itself: edit `index.html` on GitHub. The app picks up the new version the second time you open it after the change, since it loads the saved copy first and fetches the update in the background.

## Files

| File | What it does |
| --- | --- |
| `index.html` | The whole app |
| `manifest.webmanifest` | Name, icon and full-screen mode for the Home Screen |
| `sw.js` | Lets the app open without internet |
| `icon-*.png` | Home Screen icons |
