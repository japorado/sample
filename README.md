# GitHub Image Website

This folder is a ready-to-upload static website (HTML + images only).

## Upload to GitHub
1. Create a new **Public** repository on GitHub (any name is fine).
2. Upload ALL files in this folder to the repo root:
   - index.html
   - img1.jpg, img2.jpg, img3.jpg, img4.jpg

## Turn on GitHub Pages
1. In the repo, go to **Settings** → **Pages**
2. Under **Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main** (or master) and **/(root)**
3. Click **Save**

GitHub will show your live URL on the same page after it publishes.

## Optional: test locally
- Run: `python -m http.server 8000`
- Open: http://localhost:8000
