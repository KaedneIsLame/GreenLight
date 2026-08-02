GREENLIGHT — MAKE IT AN INSTALLABLE APP (free, ~10 minutes)

You already have a GitHub account from setting up sync. Now:

1. Go to github.com -> + (top right) -> New repository.
   Name: greenlight  ·  set to Public  ·  Create.
2. On the repo page: "uploading an existing file" -> drag ALL files from
   this folder (index.html, manifest.json, sw.js, icon-192.png,
   icon-512.png) -> Commit changes.
3. Repo Settings -> Pages -> Source: "Deploy from a branch" ->
   Branch: main, folder: / (root) -> Save.
4. Wait ~2 minutes. Your app is live at:
   https://YOURUSERNAME.github.io/greenlight/
5. Open that link on each device:
   - iPad/iPhone: Safari -> Share -> Add to Home Screen
   - Android: Chrome -> menu -> Add to Home screen / Install app
   - PC: Chrome/Edge -> install icon in the address bar

Now it launches full-screen like a real app, works offline after first
load, and there is ONE canonical version — update the file in GitHub and
every device gets it. Combined with sync (Settings), your history,
watchlist, and YouTube API key follow you everywhere; the only thing you
paste per device is the GitHub sync token.

Note: the page is public at that URL (anyone with the link can load the
app), but YOUR data never lives in the page — it stays in your browser
and your private gist. If you want it unlisted, pick a random repo name.
