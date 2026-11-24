# Chronicles of Kilwa - Release Notes

Public release notes for **Chronicles of Kilwa**, a VR journey through the story of Kilwa Kisiwani for Meta Quest 3.

**Live page:** https://seedexr.github.io/kilwa-releases

## How to update (every time we publish a build)

1. Open `CHANGELOG.md`.
2. Add a new version block at the **top** of the list:
   ```
   ## [0.3.0] - 2026-12-01
   One-line summary of this build (optional).

   ### Added
   - New things players can now do.

   ### Changed
   - Things that were reworked or improved.

   ### Fixed
   - Bugs squashed.
   ```
3. Commit and push.

The branded page (`index.html`) fetches `CHANGELOG.md` and re-renders automatically. You only ever edit `CHANGELOG.md`.

Use whichever sections apply (`Added`, `Changed`, `Fixed`, `Known Issues`, `Removed`). Match the version number to the app's `bundleVersion`. Write for players: describe what they can do and see, never how far along the work is.
