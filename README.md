# labs.kalibrio.com

Static GitHub Pages site for Kalibrio Labs prototypes. Every page here is an AES-256-GCM unlock page decrypted in the browser; no plaintext is ever committed.

- `/fv-banking` — FV Cooperative banking prototype

## Source

Authored in the private repo `Kalibrio/dashboard-src` (local clone `../dashboard-src`), `labs/<name>/index.html`.

## Rebuild

```bash
node ../dashboard-src/labs/build.mjs fv-banking
git add -A && git commit -m "build: fv-banking" && git push
```
