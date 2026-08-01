# Anastensia — Portfolio Website

A single-page personal-brand / portfolio site for **Anastensia Okoye** (singer · model · performer).
Static HTML + CSS + a little vanilla JS. No build step, no dependencies.

## Run / preview locally
Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Host it (free options)
Drag-and-drop the whole folder to any of these:
- **Netlify Drop** — https://app.netlify.com/drop
- **Vercel** — `vercel` in this folder
- **GitHub Pages** — push the folder, enable Pages
- **Cloudflare Pages** — connect the repo or upload

Everything is self-contained, so it works anywhere static files are served.

## File structure
```
index.html          — the whole site
assets/img/         — curated photos used on the page
assets/video/       — YouTube thumbnail posters for the video sections
assets/raw/         — the full photo library (backups to swap in)
```

## Things to update (search index.html for these)
1. **Booking email** — currently `hello@anastensia.com` (placeholder). Replace with the real one.
2. **Music track titles** — track 1 is real (`อย่าบอกว่ารัก`). Tracks 2–4 use generic titles
   (`Featured Single`, `Studio Session`, `Live Performance`) + real YouTube IDs — rename to the
   actual song titles.
3. **Sprite commercial** — links out to the Facebook video (no embeddable YouTube version).
4. **Swap photos** — replace any file in `assets/img/` with a new image of the same name, or point
   the `<img src>` at a different file from `assets/raw/`.

## Video / music links used
- Mitsubishi (YouTube `tcl0HVp7jLs`), MILO (`1drkNSxIDV0`), Garnier (`-c1fb-iYFOk`), Sprite (Facebook)
- Music: `YHoooMsdLz4`, `Wii4DusZ6L8`, `09rotBYIvwQ`, `OWi6St6IPdQ`
- Apple Music, Instagram, press (Tribune, Vanguard, The Face TH)

Videos load only when clicked (fast first paint), and the site is fully responsive.
