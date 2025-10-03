# Vertical Video Demo (GitHub Pages)

This folder is ready to publish with GitHub Pages.

## Quick publish
1. Create a new **public** repository on GitHub (e.g., `vertical-video-demo`).
2. Upload these files to the repo root (or `git push` them).
3. In **Settings ▸ Pages**, choose:
   - **Build and deployment**: *Deploy from a branch*
   - **Branch**: `main` (or `master`) and **/ (root)**
4. Save. Your site will appear at `https://<USERNAME>.github.io/<REPO>/`.

- The main page is **index.html** (optimized with portrait preference).
- Optional page **portraitLock.html** can *lock* playback to a vertical level on Chrome/Firefox.

### Notes
- If your Flowplayer token restricts playback by domain, add your GitHub Pages host to the allowlist.
- If you later use a custom domain, put that domain in the **CNAME** file and in the token allowlist too.
