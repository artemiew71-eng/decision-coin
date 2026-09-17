# 🪙 Decision Coin

A single-page app for making decisions by weighing options against criteria — and letting a coin flip settle close calls.

## How it works

1. Add **criteria** (e.g. Speed, Importance, Effort) and set a weight (1–10) for each.
2. Add the **options** you're choosing between.
3. Rate each option against each criterion with a 1–5 star score.
4. The app computes a weighted total per option and ranks them.
5. If the top options are nearly tied, a coin-flip button appears to break the tie.

All data is stored locally in the browser (`localStorage`) — nothing is sent to a server.

## Running locally

This is a static, dependency-free HTML file. Just open it in a browser:

```bash
# from this directory
start index.html   # Windows
open index.html     # macOS
```

Or serve it with any static file server, e.g.:

```bash
npx serve .
```
