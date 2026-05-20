# swym

Modified self-hostable Swym copy utility.

## Changes
- Supports multiple target communities instead of a single target.
- Allows adding and removing validated target communities.
- Copies selected content to each target community in sequence.

## Structure
- `index.html`
- `static/version.json`
- `bundle.js` (active runtime bundle)
- `bundle.dec.js` (reference/debug copy)
- `README.md`
- `README.txt`

## Hosting
Serve the repository as static files over HTTP, preserving relative paths.
The loader in `index.html` reads `static/version.json` and then loads `bundle.js`.

## Repository notes
- `bundle.js` is the active runtime asset used by the hosted app.
- `bundle.dec.js` is kept only as a readable reference/debug artifact.
- Redundant duplicate bundle files were removed to reduce repository size and avoid drift.
