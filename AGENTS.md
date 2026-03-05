# AGENTS.md

## Cursor Cloud specific instructions

This repository is a minimal static HTML site (single `index.html`) with no build tools, package managers, or dependencies.

### Running the site

Serve the project root with any static file server:

```
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000` in a browser.

### Lint / Test / Build

- **Lint**: No linter is configured. You can optionally validate `index.html` with an HTML validator.
- **Tests**: No automated tests exist.
- **Build**: No build step is required; the site is plain HTML/CSS served as-is.

### Notes

- `him-target-url.txt` is a legacy file from a previous Cloudflare redirect setup; it is effectively empty.
- The page references `http://127.0.0.1:8000` as the local access URL — this is the expected dev server port.
