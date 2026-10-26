# aw-embeds

Built scripts for akphotographer.com, served by jsDelivr. The source is private; nothing here is edited by hand.

- `call-sheet/aw-call-sheet.min.js`: the Call Sheet (Plan your session)
- `golden/aw-golden.min.js`: golden hour times for the site head
- `call-sheet/manifest.json`: version, build and integrity hashes
- `places/v1/`: the shoot map for /places (`aw-map.js`, `aw-map.css`, minified from `embeds/places` at 7d8d4bb) and its drawing (`map-art-day.svg`, `map-art-night.svg`, traced from OpenStreetMap: © OpenMapTiles © OpenStreetMap contributors)
- `places/v2/`: the shoot map v2 (`embeds/places` at 8be66d4): the city drawn with its names, and the region beyond it (`map-city-*.svg`, `map-region-*.svg`, from OpenStreetMap: © OpenMapTiles © OpenStreetMap contributors)

Each release is a tag (for example `call-sheet-0.6.1`); the site loads a tag, never a branch.
