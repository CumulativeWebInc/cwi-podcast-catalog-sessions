# Post-Trap Futurism: The Catalog Sessions

25-episode podcast series from **Cumulative Web Inc** — the story of That Boy Hi Hat's catalog,
one track per episode, hosted by Marcus and Nia.

- 🎧 Listen / browse: https://cumulativewebinc.github.io/cwi-podcast-catalog-sessions/
- 📡 Stable RSS feed: https://cumulativewebinc.github.io/cwi-podcast-catalog-sessions/feed.xml
- 📋 Directory submission steps: [DISTRIBUTION.md](DISTRIBUTION.md)

## Layout

- `episodes/` — 25 mp3s with permanent filenames (never rename; podcast clients cache these URLs)
- `cover.jpg` — 1600×1600 show art
- `feed.xml` — the submittable RSS 2.0 feed (iTunes + Podcasting 2.0 namespaces)
- `index.html` — public landing page
- `DISTRIBUTION.md` — how to submit to Spotify / Apple / Overcast / Pocket Casts

## Build

The feed was generated 2026-09-20 from the production mp3s in `~/workspace/podcasts/`
(durations via ffprobe, byte lengths measured, GUIDs stable). Episode descriptions are drawn
from each episode's script; all episodes scanned clean for profanity (`itunes:explicit: no`).
