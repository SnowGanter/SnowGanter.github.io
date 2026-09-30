# Portfolio entry point

`https://snowganter.github.io/` redirects to the English portfolio at
`https://snowganter.github.io/portfolio/`.

This repository only contains the entry point. The actual site and its deployment
are maintained in [SnowGanter/portfolio](https://github.com/SnowGanter/portfolio).

GitHub Pages is configured for the `main` branch, repository root. No custom
domain or DNS changes are required. The redirect uses `location.replace` to avoid
a Back-button loop, with a meta-refresh and visible link as fallbacks.
