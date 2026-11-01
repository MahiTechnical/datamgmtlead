# datamgmtlead

Portfolio site for **H. Mahesh — Senior Data Management Lead | Governance, Quality & AI Readiness | Financial Services**.

Static site (HTML, CSS, vanilla JavaScript). No build step, framework or backend.

**Intentionally excluded:** resume PDF, resume links, and GitHub profile links.

## Files

```text
datamgmtlead/
├── index.html          # Portfolio content
├── assets/
│   ├── css/style.css   # Design and responsive layout
│   └── js/main.js      # Mobile menu, active-section highlight, reveal effects
├── .nojekyll
└── README.md
```

## Run locally

```bash
python -m http.server 8000   # then open http://localhost:8000
```

## Publish with GitHub Pages

1. Upload the contents of this folder to the root of `MahiTechnical/datamgmtlead` (`index.html` must be at the root).
2. **Settings → Pages → Build and deployment → Deploy from a branch.**
3. Branch `main`, folder `/ (root)`, then **Save**.
4. After 1–2 minutes the site is live at **https://mahitechnical.github.io/datamgmtlead/**.

The repository must be public for Pages on a free account.

## Content rules

Every claim, title, date and figure on the site comes from the current resume. Do not add tools or experience (for example Microsoft Purview) until the resume states them. Project summaries are high-level; no confidential employer code, data or architecture is published.
