# Repository maintenance

Read README.md first.

index.html owns the JavaScript, meta-refresh, canonical and fallback destinations. This repository is an active compatibility route. Keep all four targets consistent. The current redirect uses a fixed destination; it does not preserve incoming query strings or fragments. Review incoming-link requirements before changing that behavior.

Edit only the relevant page or documented asset. Preserve unrelated utilities and existing routes.

Before a change, inspect the current branch, remote and working tree. Preserve other contributors’ changes. Do not publish private authoring notes, machine paths, correspondence or raw research.

For documentation changes, check Markdown links and git diff --check. For page or asset changes, preview the affected route, test its links and downloads, then check the deployed URL after publication. A successful Git push does not prove a Pages deployment succeeded. Preserve the previous commit for a normal revert; do not rewrite history.
