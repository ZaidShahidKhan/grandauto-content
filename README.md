# GrandAuto content

Live content for the VI Map & Cheats app. The app downloads these files on open,
so edits here reach every phone without a Play Store update.

- `content/cheats.json`: cheats
- `content/map.json`: map pins and categories
- `content/checklist.json`: Missions lists

**To publish a change:** edit a file, raise its `"version"` number, commit and push.
Phones only take a file whose `version` is higher than the one they have.
