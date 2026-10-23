# Dungeon Ledger v1.2.0

A mobile-friendly, static D&D character tracker for GitHub Pages. This package is a complete replacement pack; the files are intended to sit directly in the repository root, not inside an extra nested folder.

## What's included
- Multiple character sheets saved in the current browser/device
- D&D 5e (2014) and 2024 ruleset label
- 4d6, drop lowest ability score rolling
- Standard array (15, 14, 13, 12, 10, 8)
- 27-point buy cost/validity checker
- Ability modifiers, proficiency bonus, skills/expertise, class levels, combat values, equipment, and notes
- JSON import/export backups
- Installable manifest and app icons
- Updated service worker: network-first page loading, versioned cache, and old-cache cleanup to help updates appear

This is a character tracker and calculator, not a complete licensed reproduction of every official sourcebook. It does not provide spell tracking or automate every class feature and rule. Verify character rules against the books used at your table. Hit point totals can require manual correction, especially for multiclass characters.

## Replace the files in your existing GitHub repository (Safari on iPhone)
1. Download and extract the ZIP.
2. Open your repository on github.com.
3. For each existing file, open it and use the edit/pencil control to replace its contents, or use **Add file → Upload files** on desktop if available. The files to replace/add are `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, and `README.md`.
4. Make sure these files are in the **repository root** (same level as the README, not in a new nested folder).
5. Commit the changes to the branch/folder configured in **Settings → Pages**.
6. In **Settings → Pages**, confirm the publishing source matches that branch/folder. Wait for the latest deployment to finish successfully.
7. Open the published URL in Safari. If the old app remains, test in a Private tab first. If the Private tab is updated, remove the old Home Screen shortcut and add it again after opening the fresh site.

## Expected GitHub Pages structure
```
index.html
manifest.webmanifest
sw.js
icon-192.png
icon-512.png
README.md
```

## Backups
Use **Export** in the app to download a JSON backup. Import that JSON on the same or another device to restore character data. Browser storage is device/browser-specific; GitHub Pages does not automatically sync characters between devices.

Unofficial fan-made tool; not affiliated with Wizards of the Coast.
