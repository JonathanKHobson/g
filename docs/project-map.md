---
project: gamemasterkyle-short-link
type: project-map
status: active
---

# Project Map

- `index.html` is the public `/g/` redirect and card entrypoint.
- `assets/`, `styles/`, and `scripts/` contain the static page dependencies.
- `tools/inject-cloudflare-analytics.mjs` adds the privacy-first analytics beacon only to the generated deployment artifact.
- `.github/workflows/pages.yml` builds and deploys GitHub Pages from `main`; it requires the repository variable `CLOUDFLARE_WEB_ANALYTICS_TOKEN`.

Source HTML remains free of deployment-specific tracking code. The workflow must fail rather than publish an untracked artifact when the analytics token is missing or invalid.
