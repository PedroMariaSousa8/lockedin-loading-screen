# LockedIn loading screen

A lightweight, dependency-free recreation of the supplied loading-screen reference,
ready for GitHub Pages.

## Run locally

Open `index.html` directly in a modern browser, or serve this folder with any static file server.

For example:

```sh
python3 -m http.server 4173
```

Then visit `http://127.0.0.1:4173/`.

## GitHub Pages

Place the contents of this folder at the repository root and configure GitHub Pages
to publish from that branch. No build step or dependencies are required.

## Files

- `index.html` contains the accessible page structure.
- `styles.css` reproduces the exact sampled off-white canvas, centered LockedIn logo, and neutral-grey loading bar.
- `assets/lockedin-logo-source.png` is the supplied LockedIn artwork. The page uses it as a luminance mask, so only the exact wordmark shape is rendered and no image background is visible.
