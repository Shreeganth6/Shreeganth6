# Deploying to GitHub Pages

1. Create a new GitHub repository (e.g. `portfolio` or `yourusername.github.io`).
2. Upload these three files to the repo root: `index.html`, `style.css`, `script.js`.
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
5. Save. Your site will be live in a minute or two at:
   - `https://yourusername.github.io/repo-name/` (normal repo), or
   - `https://yourusername.github.io/` (if the repo is named `yourusername.github.io`)

No build step, no dependencies to install — it's plain HTML/CSS/JS, so it just works as static files.

## Before you publish
- Update the GitHub project links (currently `href="#"`) on the two project cards to your real repo URLs.
- Swap in your actual portfolio link if you have one, in the summary text at the top.
