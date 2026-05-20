Modified self-host package for the Swym copy tool.

Included:
- index.html
- static/version.json
- bundle.js (patched, readable JS)
- bundle.dec.js (original decompressed JS)
- bundle.patched.js (same as patched bundle.js)

Behavior changes:
- Supports multiple target communities.
- ADD button appends validated target communities to a list.
- Selected targets can be removed.
- Copy action iterates over all target URLs.

Host as static files, preserving relative paths.
