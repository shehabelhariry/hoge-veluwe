# The Veluwe Field Test

A two-player trivia trail through **De Hoge Veluwe National Park** — the heath, the deer, the free white bikes, Van Gogh, and the legend of the silver cross in the stag's antlers. Built as a fun game for a couple's day out.

It's a single, self-contained `index.html` — no build step, no dependencies. Open it in a browser and play.

## What's inside

- **Two-player quiz** — take turns along a 12-marker trail; each answer reveals a field note with a source link.
- **Getting there from Amsterdam** — the train + bus route, with a verdict on timing.
- **What to pack** — a tappable checklist.
- **Field notes & fun facts** — twelve things worth knowing about the park.
- Light/dark themes and a mobile-first responsive layout.

## Running locally

Just open `index.html`, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which publishes the static site to **GitHub Pages**.
Live at: https://shehabelhariry.github.io/hoge-veluwe/

## Sources

Facts gathered from [hogeveluwe.nl](https://hogeveluwe.nl/en), [krollermuller.nl](https://krollermuller.nl/en) and [nationaleparken.nl](https://nationaleparken.nl/en). Verify opening hours, prices and transport times before you go.
