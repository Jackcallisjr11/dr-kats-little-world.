Dr. Kat's Little World — Mobile Layout Repair

This build keeps the existing game systems and adds a full-screen illustrated island backdrop plus mobile HUD spacing repairs.

Publish/update steps:
1. Extract this ZIP.
2. Upload and replace these files in the ROOT of the existing GitHub Pages repository:
   index.html
   island-art.png
   manifest.webmanifest
   icon.svg
   sw.js
   README.txt
3. Commit the changes to main and wait for the GitHub Pages workflow to finish.
4. Open the live site in a private/incognito tab or clear the site cache if the old layout remains cached.

The game stores progress locally in the browser. Use Settings > Export backup / Import backup to transfer progress between devices.

Note: This repair fixes the mobile layout and adds the illustrated background. The current CSS-built Kat and Jack figures are still placeholders, not finished custom sprite sheets. Test on the target phone after deployment.
