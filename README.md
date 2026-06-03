# Preview Studio

A self-contained page for previewing three assets in realistic platform mockups
(YouTube 1920×1080, podcast tile 600×600, social image 1080×1350) and sharing a
preview-only link with anyone.

There is only one file: **`preview-studio.html`**. No build step, no dependencies.

---

## How to use it

1. Open the hosted page (your GitHub Pages URL — see below).
2. On the left, upload your three images (drag-and-drop or click). Each one
   drops into its mockup live. Images are automatically resized and compressed
   so the share link stays small.
3. Click **Copy share link**. This packs your images into the URL itself.
4. Paste that link to anyone. They see **only the preview** — no editor,
   no upload controls.

You can change images and generate a new link anytime. Nothing you upload is
stored in this repository — the images travel inside the link.

> **Backup option:** **Download host-ready file** exports a preview-only HTML
> with the images baked in, in case a link ever gets too long for very large
> images. Drop that file on any static host for a permanent URL.

---

## Hosting on GitHub Pages (one-time setup)

1. Create a new repository (e.g. `preview`) and add this `preview-studio.html`
   file to it.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set:
   - **Source:** Deploy from a branch
   - **Branch:** `main`  ·  Folder: `/ (root)`
4. Save and wait ~1 minute.
5. Your page is live at:
   `https://YOURUSERNAME.github.io/REPONAME/preview-studio.html`

Open that URL, upload your assets, click **Copy share link**, and share.

---

## Notes

- The clipboard copy works because GitHub Pages serves over `https://`.
- The recipient needs no account and uploads nothing — they only view.
- Mockup style is fixed to the realistic platform framing.
