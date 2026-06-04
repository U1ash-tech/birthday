# Amma Birthday Website

This is a static website built with HTML, CSS, and JavaScript. It is ready to share as a website link or as a downloaded package.

## Best way to share

### Option 1: Publish on Netlify (recommended)
1. Zip the project folder (`index.html`, `style.css`, `images/`, `videos/`, `slideshow/`).
2. Go to https://app.netlify.com/drop
3. Drag and drop the ZIP file onto the page.
4. Netlify will host the site and give you a public URL that works on laptops and Android phones.

### Option 2: Publish on GitHub Pages
1. Create a GitHub repository.
2. Push this folder to the repository.
3. In GitHub repo settings, enable GitHub Pages from the `main` branch, root folder.
4. GitHub will provide a public URL.

### Option 3: Share the ZIP directly
1. Zip the project folder.
2. Send the ZIP to someone.
3. They can open `index.html` in a browser.

> Note: For the slideshow music to work, place a music file at `slideshow/music.mp3`.

## Important notes

- Keep all files in the same folder structure.
- If you add videos, name them sequentially as `video1.mp4`, `video2.mp4`, etc.
- If `video6.mp4` is missing, the code now skips gaps and continues scanning.
- For mobile access, use the public URL provided by Netlify or GitHub Pages.

## Recommended deployment flow

1. Open the project root folder.
2. Create a ZIP file of the whole folder.
3. Upload it to Netlify Drop.
4. Share the generated public URL.
