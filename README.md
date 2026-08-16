# Clips Search (standalone)

Static single-page app that searches the Supabase clips library.

## Deploy to your own Vercel account (2 min)
Option A — Vercel CLI (recommended):
  1. Open a terminal in this folder.
  2. Run:  npx vercel
     - Log in with YOUR Vercel account when prompted.
     - Accept the defaults (framework: Other; it's a static site).
  3. Run:  npx vercel --prod   (to publish the production URL)

Option B — Drag & drop (no CLI):
  1. Go to https://vercel.com/new
  2. Choose "Deploy" > drag this whole folder in (or "Import" a Git repo if you push it to GitHub).

The app is index.html; vercel.json sets the headers so Supabase + video playback work.
