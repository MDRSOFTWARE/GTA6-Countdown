GTA VI LIGHTSTREAM PARALLAX COUNTDOWN
=====================================

FILES
- index.html: the full 1920x1080-friendly countdown webpage
- config.js: countdown date, slideshow duration, and image filenames
- backgrounds/: place ten JPGs here, named 01.jpg through 10.jpg

IMPORTANT: The ZIP does NOT contain official GTA VI artwork. Add images you
have permission to use. If images are missing, their slides show the fallback
colour background. The site works without external image hosting.

LOCAL PREVIEW
1. Extract the ZIP.
2. Add your 10 images to the backgrounds folder.
3. Double-click index.html in Chrome or Edge.
4. Check the images and countdown. For a closer GitHub Pages preview,
   run `python -m http.server 8000` from the extracted folder and open
   http://localhost:8000 in your browser.

GITHUB PAGES (FREE)
1. Create a PUBLIC GitHub repository (for example gta6-countdown).
2. Upload index.html, config.js, and the backgrounds folder with all 10 JPGs
   into the repository ROOT (not a nested folder). Commit changes.
3. Repository Settings > Pages > Deploy from a branch > main > /(root) > Save.
4. Wait for the Pages deployment. Open the published HTTPS URL, typically
   https://YOUR-USERNAME.github.io/gta6-countdown/
5. If a previous version appears, refresh the browser / Lightstream source.

LIGHTSTREAM
1. Open your Lightstream Studio project.
2. Add a browser/webpage source (or the equivalent third-party browser layer).
3. Paste your GitHub Pages URL.
4. Size the layer to the full 16:9 canvas and put it in the desired scene.
5. If gameplay must remain visible, put the countdown on a separate waiting
   room scene. This is an opaque full-screen background, not a transparent HUD.

CUSTOMIZATION
- In config.js, edit targetISO to an explicit ISO timestamp with offset.
  The initial target is 2026-11-19 00:00:00 NZDT (+13:00), as requested.
- Edit slideSeconds to change the default 20-second duration.
- Replace any JPG with another JPG of the same filename; no HTML edit needed.
- Image recommendation: landscape 1920x1080, optimized JPG around 300-800 KB.
- NZ clock uses the Pacific/Auckland timezone and automatically adjusts DST.
- The camera-style parallax is a 2.5D effect, not true 3D reconstruction.

IMAGE SOURCES
Rockstar official GTA VI artwork page:
https://www.rockstargames.com/VI/media/artwork-wallpapers
Check image usage rights before broadcasting publicly.
