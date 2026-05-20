# swym

Modified self-hostable Swym copy utility.

## Changes
- Supports multiple target communities instead of a single target.
- Allows adding and removing validated target communities.
- Copies selected content to each target community in sequence.

## Structure
- `index.html`
- `static/version.json`
- `bundle.js`
- `bundle.dec.js`
- `bundle.patched.js`
- `README.md`
- `README.txt`

## Hosting
Serve the repository as static files over HTTP, preserving relative paths.
The loader in `index.html` reads `static/version.json` and then loads `bundle.js`.
