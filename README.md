# Tilted — OG Fortnite Build Archive

A single-page site for finding and downloading old Fortnite builds, sorted by chapter and season.

## Adding or editing builds

Everything lives in `index.html`. Scroll to the `SEASONS` list near the bottom (look for **EDIT YOUR BUILDS HERE**).

Each build looks like this:

```js
{ v: "12.41", note: "Travis Scott event", size: "26 GB", url: "https://your-link-here" },
```

- `v` – version number
- `note` – optional label shown under the version
- `size` – optional
- `url` – the download link. Leave it as `""` and the button shows **Soon**.

Season cards, totals, search and the build popup all update automatically.

## Hosting

Turn on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root) and the site is live.

---
Fan-made archive. Not affiliated with or endorsed by Epic Games.
