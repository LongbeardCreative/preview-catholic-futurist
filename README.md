# Preview Studio

Preview three assets in realistic platform mockups (YouTube 1920x1080, podcast
tile 600x600, social image 1080x1350) and share a **preview-only** page where
the images are baked in and the editor is hidden.

Main file: **`preview-studio.html`** — the editor. No build step, no dependencies.

---

## The workflow (GitHub Pages)

1. Open the hosted editor:
   `https://longbeardcreative.github.io/preview-catholic-futurist/preview-studio.html`
2. Upload your three images on the left (drag-and-drop or click).
3. Set a **Share page filename** (e.g. `futurist-preview`).
4. Click **Create share page**. This downloads a single HTML file with your
   images baked in, set to open in preview-only mode.
5. Upload that file to this repo (**Add file -> Upload files -> Commit**).
6. Your shareable link is:
   `https://longbeardcreative.github.io/preview-catholic-futurist/FILENAME.html`

Send that link. The recipient sees **only the three mockups** — no editor,
no upload controls, images included.

To share a different set of images, repeat: create a new share page (give it a
new filename), upload it, share its URL.

---

## Buttons

- **Create share page** — the reliable share path. Bakes images into a
  preview-only HTML file to upload to GitHub. No size limits.
- **Copy quick link (small images)** — packs images into the URL itself.
  Only works for very small images; optional. For real assets, use Create
  share page instead.
- **Clear all** — reset the uploads.

---

## Notes

- Images are auto-resized and compressed on upload.
- The recipient needs no account and uploads nothing — they only view.
- Mockup style is the realistic platform framing.
