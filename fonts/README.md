Self-hosting Cascadia Code

1. Download the latest release zip from the official repo:
   https://github.com/microsoft/cascadia-code/releases/latest

2. From the release assets, extract the following files (WOFF2 preferred):
   - CascadiaCode-Variable.woff2
   - CascadiaCode-Italic-Variable.woff2

   (Optional: include the .ttf files if you prefer.)

3. Place those files into this folder (`fonts/`).

4. Commit these files to your repo (they're SIL Open Font License — check the repo LICENSE if you need confirmation).

5. Reload the site; the fonts will be preloaded from `/fonts/` and used automatically by the CSS.
