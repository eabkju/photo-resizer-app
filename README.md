# Pure Offline Image Resizer

A privacy-first, browser-based image resizing and editing app. It works entirely in the browser, keeps your images local, and allows you to crop, resize, apply filters, add text overlays, and export processed files without uploading anything to a server.

## Features

- Upload JPG, PNG, and WEBP images
- Crop using an interactive editor
- Resize by pixels, percentages, inches, centimeters, or millimeters
- Lock aspect ratio while adjusting dimensions
- Preset size options for common social and print formats
- Apply grayscale, sepia, invert, brightness, contrast, and saturation controls
- Add text overlays with custom font, size, color, and positioning
- Export in JPG, PNG, WEBP, BMP, GIF, or AVIF formats
- Optional max file-size setting for compressed JPG/WEBP output

## Run locally

Because this is a static HTML app, you can open `index.html` directly in a browser or serve it locally.

### Option 1: open directly

- Open `index.html` in any modern browser.

### Option 2: local static server

```bash
cd photo-resizer-app
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deployment

This project is configured as a static site and can be deployed to GitHub Pages or any static hosting provider.

### GitHub Pages

1. Push this repository to GitHub.
2. Open the repository on GitHub.
3. Go to Settings > Pages.
4. Set Source to "Deploy from a branch".
5. Select the `main` branch and `/ (root)` folder.
6. Save.

Your site will be published at:

```text
https://<your-username>.github.io/photo-resizer-app/
```

## Notes

- No server-side processing is used.
- Images are processed locally in the browser.
- The application is designed for offline-friendly usage and privacy-conscious workflows.
