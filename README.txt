DR. KAT'S LITTLE WORLD — PROTOTYPE 18
======================================

WHAT'S NEW
- Prepared as a public-launch package for GitHub Pages.
- Added installable web-app metadata (manifest + icon).
- Added a service worker to cache the game shell for repeat/offline opening.
- Preserved the complete Prototype 17 game HTML and its existing features,
  including manual JSON backup import/export.

IMPORTANT
- This package is NOT published yet. No public URL exists until you upload it
  to a public GitHub repository and enable GitHub Pages.
- Save data remains in the browser on each device. There is no automatic
  cloud sync between your phone and Dr. Kat's phone.
- The current character artwork is still the prototype's CSS-drawn placeholder
  style; final custom character sprite artwork has not been integrated.
- Service-worker/offline behavior requires the game to be hosted over HTTPS
  (GitHub Pages provides HTTPS).

PUBLISH WITH GITHUB PAGES
1. Create a NEW public GitHub repository.
2. Upload every file in this folder (index.html, manifest.webmanifest,
   icon.svg, sw.js, README.txt) to the repository root.
3. Open repository Settings -> Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select branch "main" and folder "/ (root)", then Save.
6. Wait for GitHub Pages to finish deploying. Copy the published URL and
   open it on your phone to test before sending it to Dr. Kat.

The URL usually looks like:
https://YOUR-USERNAME.github.io/REPOSITORY-NAME/
