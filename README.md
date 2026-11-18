# Kabir Gupta · Portfolio

My portfolio site, written as a markdown file you scroll through. Follow the Rubik's cube: it moves to a new spot in every scene and solves itself in 19 moves by the end. 12 seconds is my real PB.

What's on it: MediTrack, This vs That, my ShunyaLabs internship, my two research papers, and what I do outside of building.

## Files

- `index.html`: the whole site
- `KABIR.md`: everything on the site as plain markdown, for people and AI agents
- `_headers`: tells Netlify to serve `KABIR.md` as readable text
- `img/`: photos and screenshots
- `papers/`: the This vs That paper (PDF)

No build step. The cube uses Three.js, loaded from a CDN.

## Run it

Open `index.html` in a browser. Or serve the folder:

```
python3 -m http.server
```

## Deploy

Live at https://kabirgupta.me, hosted on Netlify from this repo. Build command: none. Publish directory: the repo root.
