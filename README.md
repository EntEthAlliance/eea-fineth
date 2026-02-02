# EEA unified webpage (GitHub Pages)

This folder is ready to publish as a static site on GitHub Pages.

## Files
- `index.html` (tabs container)
- `why-ethereum-works.html`
- `ethereum-architecture-overview.html`
- `global-finance-map.html`

## Publish via GitHub Pages (recommended: project pages)

1. Create a repo (or use an existing one).
2. Upload these files to the repo root (same folder level).
3. In GitHub: **Settings → Pages**
4. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main` (or `master`) / root
5. Save. Your site will be available at:
   - `https://<username>.github.io/<repo>/`

## Notes
- The three original pages are loaded in an iframe to avoid CSS/JS collisions.
- Deep links work: `#why`, `#architecture`, `#finance`
