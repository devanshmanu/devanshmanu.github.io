# devanshmanu.github.io

Landing redirect for my music. Live at: https://devanshmanu.github.io/

Right now it redirects to my smart link (pre-save / stream):
**https://ffm.to/kyatubhi**

## How to repoint it later
Edit the URL in **two places** in `index.html`:
1. `<meta http-equiv="refresh" content="0; url=...">`
2. `window.location.replace("...")`
(Also update `404.html` if you want mistyped paths to follow.)
Commit → the printed QR keeps working, new destination applies.

## Files
- `index.html` — the redirect page (edit this to repoint)
- `404.html` — catches any other path, redirects too
- `.nojekyll` — serve files as-is on GitHub Pages
