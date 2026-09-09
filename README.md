# Frenetic Frequency — GitHub Pages

This version removes the JPEG completely and uses YouTube instead.

## 1. Add your YouTube video

Open `index.html` and find:

`YOUR_YOUTUBE_VIDEO_ID`

If your video is:

`https://www.youtube.com/watch?v=ABC123XYZ`

the ID is:

`ABC123XYZ`

Replace **both** occurrences of `YOUR_YOUTUBE_VIDEO_ID` in `index.html`.

## 2. Optional: change the YouTube button

The YouTube button currently points to `https://www.youtube.com/`.
Replace it with your official channel URL when ready.

## 3. GitHub Pages

Upload these files to the root of your repository:

- `index.html`
- `style.css`

No JPEG, PHP, XAMPP or Cloudflare Tunnel is required.

Then:

GitHub → Repository → Settings → Pages → Deploy from branch → `main` → `/ (root)`

The site will be served by GitHub Pages.

## Important

The visual design keeps the black / acid-green / psychedelic aesthetic from the tested version, but the old JPEG dependency is gone.
