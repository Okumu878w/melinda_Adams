# Melinda Adams — Portfolio Site

## Files
- `index.html` — the entire website (self-contained)
- `vercel.json` — Vercel deployment config

## How to Add Your Photo

1. Add your photo file (e.g. `melinda.jpg`) to this folder.
2. Open `index.html` and find the comment that says:
   ```
   <!-- TO ADD YOUR PHOTO: ...  -->
   ```
3. Replace the entire `<div class="photo-placeholder">...</div>` block with:
   ```html
   <img src="melinda.jpg" alt="Melinda Adams" />
   ```
4. Save the file.

## Deploy to Vercel

### Option A — Drag & Drop (easiest)
1. Go to https://vercel.com and sign in / create a free account.
2. Click **"Add New Project"** → **"Deploy"**.
3. Drag this entire folder into the upload area.
4. Click **Deploy** — your site will be live in seconds.

### Option B — GitHub (recommended for updates)
1. Push this folder to a GitHub repository.
2. Go to https://vercel.com → **"Add New Project"**.
3. Import your GitHub repo.
4. Vercel auto-detects the static site — click **Deploy**.
5. Every time you push to GitHub, the site updates automatically.

## Customisation
- Replace `[Your Name]` fields with your actual details (already filled from your proposal).
- To change colours, edit the `:root` CSS variables at the top of `index.html`.
- All content is in a single `index.html` — easy to edit.
