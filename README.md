# Dungeon Ledger v1.3.0

A mobile-friendly static D&D character tracker for GitHub Pages. Upload every file in this folder directly to the repository root.

## New in v1.3.0
- Class feature reminders automatically appear based on each class and level entered.
- Multiclass prerequisites check ability scores before allowing an added class. Fighter accepts Strength 13 **or** Dexterity 13; the other classic prerequisites are checked as shown in the app.
- Class features update when you change class levels or ability scores.
- Includes 4d6-drop-lowest rolls, standard array, 27-point buy, skill calculations, character import/export, mobile styling, app icons, and versioned service-worker caching.

## Install/update from Safari on iPhone
1. Download and extract the ZIP in Files.
2. Open your GitHub repository and upload/replace `index.html`, `manifest.webmanifest`, `sw.js`, both icons, and `README.md` in the repository root.
3. Commit to the branch/folder configured under Settings → Pages. Wait for the latest deployment to succeed.
4. Open the published site in a Safari Private tab to test the new version. If it is updated there but not in your Home Screen shortcut, remove the old shortcut and add it again from the fresh site.

## Rules note
Feature reminders are concise summaries for the 2014-style core class progression, with a few rules-version-neutral labels where progressions differ. They are not full official rules text. Subclass feature details, spells, optional features, species/background features, and every 2024-specific progression are not fully automated. Verify exact rules with the books used at your table. The app does not include spell tracking.

Characters are saved in browser storage on the current device. Use Export for backups; GitHub Pages does not sync character data between devices.
