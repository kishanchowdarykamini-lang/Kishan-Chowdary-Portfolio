# Kishan - Portfolio (Vercel)

Static site: `index.html` + `images/` (full-quality originals). No build step.

## Deploy on Vercel
1. Put this folder in a GitHub repo (or drag the folder into vercel.com/new).
2. Framework preset: **Other**. Build command: empty. Output directory: `.`
3. Deploy. Add your own domain under Project > Settings > Domains.

## Add more design work
In `index.html`, find `<div class="gal" id="gal">` and copy one `<figure class="work rv" ...>` block: put the image in `images/`, set `src`, set `data-cat` to `movie`, `brand` or `event`, and edit the caption.

## Add App Store screenshots
Find `<div id="appstore"`. Each app has a `<div class="shots">` row: add `<img src="images/appstore/your-file.jpg" alt="...">` inside it, or copy a whole `<div class="app">` block for a new app.
