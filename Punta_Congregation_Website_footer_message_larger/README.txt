PUNTA CONGREGATION — LOCAL FOR A DAY 2026 WEBSITE

FILES
- index.html: welcome page
- photos.html: photo gallery with click-to-view lightbox, left/right navigation, keyboard arrows, and download link
- videos.html: future video highlights page
- styles.css: website styles
- assets/: Philippines 2026 logo, congregation group photo, and 14 behind-the-scenes photos

PREVIEW LOCALLY
1. Extract this ZIP.
2. Double-click index.html to preview the welcome page.
3. Click Photo Gallery to view the gallery. Photos can be opened, browsed left/right, and downloaded.

PUBLISH WITH GITHUB + NETLIFY
1. Create/open your GitHub repository for this site.
2. Upload the CONTENTS of this folder (index.html, photos.html, videos.html, styles.css, assets folder, README.txt) to the repository root.
3. If Netlify is already connected to that repository, it should deploy automatically after you commit the files. Otherwise, in Netlify choose Add new site > Import an existing project, connect GitHub, select this repository, leave build command blank, and set publish directory to the repository root (or ./).
4. Open the Netlify URL and test all pages and downloads.

ADDING MORE PHOTOS LATER
Add new images to assets/behind-the-scenes/ and add their paths to the prepPhotos array in photos.html. Keep filenames simple (letters, numbers, hyphens; no special characters). Upload/commit the changed files. Netlify will redeploy.

PRIVACY
This is a public static website. Anyone with the URL may be able to view and download published photos. Please only publish photos you have permission to share.
