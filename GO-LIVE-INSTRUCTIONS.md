# YUNO — How to Take It Live (5 minutes, free)

The site is a plain static website (no database, no server code), so it can go live on any free host. Fastest option first.

## Option 1 — Netlify Drop (fastest, free, ~2 minutes)
1. Go to https://app.netlify.com/drop
2. Drag the entire **NEW INFORMATION** folder onto the page.
3. Done — you get a live URL immediately (e.g. `yuno-xyz.netlify.app`).
4. To use a custom domain later (e.g. `yuno.co.za`): Netlify → Domain settings → Add custom domain.

## Option 2 — GitHub Pages (free, gives you version history)
1. Create a free GitHub account, make a new repository called `yuno`.
2. Upload all files from the NEW INFORMATION folder ("Add file → Upload files").
3. Repository → Settings → Pages → Source: `main` branch → Save.
4. Live at `https://<your-username>.github.io/yuno/`.

## Option 3 — Vercel (free, best if the site grows)
1. vercel.com → sign up → "Add New Project" → drag the folder in.

## Adding a new post (what the Mon–Thu routine does)
1. A new `.html` file goes into the `posts/` folder (copy an existing post as the template — it already has the styling, byline and One Truth block).
2. A new card is added to the top of the grid in `index.html`.
3. Re-drop the folder on Netlify (or re-upload to GitHub) — the site updates instantly.

## House rules baked into every post
- Byline and conclusion credited to **Sinethemba Ngcamu**.
- Multiple published sources per post, listed in a "Sources consulted" box.
- Ends in a single "One Truth" conclusion — never "it depends."
- Dark psychology is covered strictly as awareness/self-defence — nothing that teaches harm, targets real people, or touches controversy.
