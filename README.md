# Waste to Worth

A browser game that teaches the business side of the circular economy. Players find abundant waste materials around the world, match them to products backed by peer-reviewed research on material substitution, choose a circular business model and strategy levers, and see the economic, environmental and social results.

## Play locally
Open `index.html` in any modern browser. No build step or dependencies.

## Publish with GitHub Pages
1. Create a new repository and upload `index.html` (and this README).
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute, the game is live at `https://<your-username>.github.io/<repo-name>/`.

## What's inside
- 12 regions and waste streams, each linked to a peer-reviewed source with a DOI
- 5 circular business models (circular supply, resource recovery, product life extension, product-as-a-service, sharing platform)
- 6 strategy levers, each region with a key barrier to solve
- Random market and policy events
- Portfolio, research library, glossary and how-to-play screens
- Progress saved in the browser (localStorage), light and dark themes, mobile-friendly

## Editing content
All game content is in the `REGIONS`, `MODELS`, `LEVERS`, `EVENTS`, `FOUNDATIONS` and `GLOSSARY` arrays near the top of the `<script>` in `index.html`. To add a region, copy an existing entry, set `lon`/`lat`, and add a verified citation with a DOI.

## Disclaimer
Game economics are simplified and in game units. Summaries of research are paraphrased; read the original papers for details.
