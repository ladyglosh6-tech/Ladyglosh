# Fashion Media Gallery (example)

This small example demonstrates a simple HTML/CSS/JS gallery that loads images and videos from a JSON "data" file and displays them on a web page.

Features:
- Loads items from `data.json`
- Supports remote URLs and inline image data URIs (SVG or base64)
- Lazy loading of images
- Modal preview for larger image and video playback
- Simple filtering by text and toggle to hide/show videos

How to use:
1. Put all files in the same folder on a static web server (or open `index.html` from a local file—fetch may require a local server).
2. Edit `data.json` to add or replace items:
   - For images, use either "image_url" (remote URL) or "image_data" (data URI, e.g., "data:image/png;base64,...").
   - For videos, set "video_url" and optionally "poster".
3. Open `index.html` in your browser. The gallery will load and show items.

Notes and tips:
- Replace sample remote URLs with your own hosting or data URIs if you want self-contained files.
- Videos are linked to example MP4s; if you embed larger videos, consider using thumbnails and lazy-loading.
- For production, add error handling, authentication for private assets, and optimize images/videos for web delivery.

License: Use these templates and adapt for your project.