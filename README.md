# Amsterdam Data Union — one-page pitch

A one-slide intro to ADU, used when introducing ADU on video calls.

**Live:** https://tqueen92.github.io/adu-pitch/

## What's on the page

- Tagline: "A trusted network of data people."
- Values: Share openly · No sales pitch · Small room, face to face
- Stats: events, speakers, companies, followers
- Logos of companies that have been on stage

## What's in this repo

- `index.html` — the whole page (HTML, CSS and JS in one file)
- `images/` — company logos (PNG), flat in one folder

## Common updates

- **Values:** `div.values` in `index.html` (short versions of the website values)
- **Stats:** `ul.nums`
- **Logos:** add the PNG to `images/`, then add an `<li><img ...></li>` line to `ul.logos`. Update "companies" to match.

Keep tagline, values and stats in sync with the website: https://github.com/tqueen92/adu-website

## Publishing

GitHub Pages publishes from `main`. Changes go live 1–2 minutes after a commit. Use a hard refresh (Cmd + Shift + R) to see them.
