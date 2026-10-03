# Lumen Lab site

Support and privacy pages for Lumen Lab apps, served with GitHub Pages.

GitHub Pages serves the `gh-pages` branch, not `main`. After merging to `main`, fast-forward it: `git push origin origin/main:gh-pages`.

- Owlight support: `owlight/support/`
- Owlight privacy policy: `owlight/privacy/` (source of truth: `docs/PRIVACY_POLICY.md` in the Owlight repo; change both together)
- SetNote (세트노트) web app: `setnote/`. Build output, do not edit here: run `node scripts/build-web.mjs` in the SetNote repo and copy its `dist/` into `setnote/`.
- Fortamo support: `fortamo/support/`
- Fortamo privacy policy: `fortamo/privacy/` (source of truth: `docs/privacy/index.html` and `docs/support/index.html` in the Fortamo repo; copy them here unchanged)
