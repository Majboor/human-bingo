# Human Bingo

A pair of self-contained, static web pages built for a Platform & Web Engineering session.

## Pages

| File | Description |
| --- | --- |
| `bingo-web.html` | Human Bingo · Platform & Web Engineering |
| `bingo-archives.html` | Human Bingo · Archives, Research & Culture |

Each page ships with a companion audio script (`audio-web.js`, `audio-archives.js`).

## Run locally

The pages are fully static — any HTTP server works:

```bash
python3 -m http.server 8000
```

Then open:

- http://127.0.0.1:8000/bingo-web.html
- http://127.0.0.1:8000/bingo-archives.html
