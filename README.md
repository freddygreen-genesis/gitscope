# GitScope

Find commit emails for a GitHub user and export a repo's contributors to CSV.

## Install as a Chrome app (via GitHub Pages)

1. On GitHub, create a new **public** repository (e.g. `gitscope`).
2. Click **Add file → Upload files** and drag in everything in this folder (`index.html`, `manifest.webmanifest`, `sw.js`, the `icons` folder). Commit.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute, open `https://<your-username>.github.io/gitscope/` in Chrome.
5. Click **Install app** in GitScope's header (or the install icon in Chrome's address bar).
6. Open Token & settings in the installed app and paste your token.

The app then lives in `~/Applications/Chrome Apps` and in Launchpad; right-click its Dock icon → Options → Keep in Dock.

Your token is only stored in your own browser. The hosted page contains no secrets.
