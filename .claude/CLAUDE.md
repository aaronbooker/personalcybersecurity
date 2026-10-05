# Project instructions

This repo is the source for **aaronbooker.com**. GitHub Pages serves it from the root of the `main` branch, so anything merged into `main` goes live on the public site.

## Working rules

- Never push to `main`. Work on a branch and open a pull request; Aaron reviews and merges. A ruleset on `main` enforces this.
- Aaron edits files himself. Before changing anything, fetch the latest `main` and re-read the current version of the file. Never overwrite his edits.
- Keep the site as static files with no build step.
- Don't change or delete `CNAME`; it sets the custom domain.
- Every file outside a hidden folder (one starting with `.`) is publicly served. Keep notes, drafts and anything private out of the repo root, or in `.claude/`.

## Site notes

- `index.html` is the whole site. The talk's PowerPoint is embedded in it as base64, so updating the slides means re-embedding the new .pptx into `index.html`.
- GitHub Pages caches aggressively. After a merge, check the live site with a hard refresh before calling a change done.
