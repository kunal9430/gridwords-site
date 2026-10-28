# Grid Words website

Static site (no build step). Host it with **GitHub Pages**: Settings > Pages > Deploy from branch > `main` / `/ (root)`.

## Publishing a new APK
1. Copy the new build to `apk/GridWords.apk` (overwrite the old one, keep the exact name).
2. Optional: edit `apk/version.json` (`versionName`, `size`, `date`, `notes`). The page shows it next to the download button.
3. Commit and push. The download buttons always point at `apk/GridWords.apk`.

Files over 100 MB can't go in a normal git repo; a Grid Words APK is far below that.
To use a different file name or location, change `APK_PATH` at the bottom of `index.html`.
