# Repository Instructions

- This is a dependency-free static site. There is no package manager, build step, test runner, linter, or dev server to install or run.
- The entire application is `index.html`: inline CSS, quiz data, scoring logic, and UI behavior all live there.
- For local verification, open `index.html` directly in a modern browser and complete the 14-question flow; check back navigation, restart, result rendering, and sharing/copy fallback when relevant.
- Quiz questions, parameter keys, profile weights, and result text are data in `index.html`; keep parameter keys consistent across answers, `DATA.params`, and profile weights.
- The scoring model and near-result/tie behavior are documented in `README.md`; update that documentation if the model or user-visible behavior changes.
- GitHub Pages deployment is configured manually from the repository root; do not add a build/deploy pipeline unless the project requirements change.
