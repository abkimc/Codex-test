# NetShield TD (HTML)

A small browser game that combines tower defense and networking design:

- Build towers on the map.
- Connect towers into routes.
- Defend against incoming traffic waves (Normal, Burst, DDoS, Stealth, Priority Hijack).
- Keep route count within the policy range (minimum and maximum routes) to avoid penalties.

## Run locally

Open `index.html` directly in your browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy to GitHub Pages

Push this repository and configure GitHub Pages to serve from the default branch root.
Because the game is a single static `index.html`, it works directly on Pages.
