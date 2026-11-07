# Tilted — OG Fortnite Build Archive

A single-page site for finding and downloading old Fortnite builds, sorted by chapter and season.

## Adding or editing builds

Everything lives in `index.html`. Scroll to the `SEASONS` list near the bottom (look for **EDIT YOUR BUILDS HERE**).

Each build looks like this:

```js
{ v: "12.50", size: "26 GB", magnet: "magnet:?xt=urn:btih:...", url: "" },
```

- `v` – version number
- `note` – optional label shown under the version
- `size` – optional
- `magnet` – the build's magnet link → shows a **Torrent** button
- `url` – optional direct download link → shows a **Download** button
- Leave both as `""` and the button shows **Soon**.

Season cards, totals, search and the build popup all update automatically.

## Discord link

In `index.html`, set `DISCORD_URL` (just above the `SEASONS` list) to your invite link. It updates all three Discord buttons.

## Donation link and welcome popup

`DONATE_URL` (next to `DISCORD_URL`) sets every Support button. New visitors see a welcome popup once; set `SHOW_WELCOME = false` to turn it off.

## Launcher download

Set `LAUNCHER_URL` (next to `DONATE_URL`) to your launcher's download link and the **Download Launcher** buttons appear (top section, welcome popup, How-to step 3). Leave it `""` to hide them.

## Season cover art

Put images in `assets/seasons/` — see the README in that folder for the file names.

## Hosting

Turn on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root) and the site is live.

---
Fan-made archive. Not affiliated with or endorsed by Epic Games.
