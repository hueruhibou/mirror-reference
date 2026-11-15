# Mirror Reference v12

A lightweight, browser-based reference image board.

## Run

Open `index.html` in a modern browser. No build step or server is required.

## v12 fix

- Restoring a thumbnail no longer recenters the workspace when other images are already visible.
- The stored image returns to its previous canvas coordinates, leaving existing images in place.
- If the workspace is empty, the restored image is centered for convenience.

Thumbnail click stores or restores an image. Trackpad pinch and Ctrl+wheel do not resize images.
