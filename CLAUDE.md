# Secondary School Guidance Counsellors - Presentation

## What this is
Single-page HTML presentation: "The Power of Curiosity in the Age of AI" by Victor del Rosal.
Hosted via GitHub Pages at `victordelrosal.com/secondary-school-guidance-counsellors/`.

## Repo structure
- `index.html` : the entire presentation (slides + mobile landing page)
- `img/` : slide images
- Root-level assets: compass, elephant, NCI logo, audio

## How to commit and deploy

**The source file lives outside this repo:**
```
/Users/victordelrosal/Dropbox/Dropbox24/fiveinnolabs/SmallBets/LUX/secondary-school-guidance-counsellors/secondary-school-guidance-counsellors.html
```

**This repo is cloned to:** `/tmp/ssgc-repo` (ephemeral; re-clone if missing)

**Workflow:**
1. Edit the source file at the Dropbox path above
2. Clone or verify the repo exists:
   ```
   gh repo clone victordelrosal/secondary-school-guidance-counsellors /tmp/ssgc-repo
   ```
3. Copy the updated file as `index.html`:
   ```
   cp <source-path>/secondary-school-guidance-counsellors.html /tmp/ssgc-repo/index.html
   ```
4. Commit and push from `/tmp/ssgc-repo`:
   ```
   cd /tmp/ssgc-repo && git add index.html && git commit -m "message" && git push
   ```
5. GitHub Pages auto-deploys from `main` branch

**Do NOT commit this file to the `lux-alpha` repo.** The `.gitignore` there blocks it, and it belongs here.

## GitHub Pages
- Custom domain: `victordelrosal.com`
- Path: `/secondary-school-guidance-counsellors/`
- Branch: `main`, root `/`
- HTTPS enabled
