# x-clone

A small, front-end clone of the X (formerly Twitter) interface built with plain HTML, CSS and JavaScript using Vite as the dev server/bundler. This repo is a simple UI exercise — great for learning DOM manipulation, layout, and small-scale state handling.

## Quick demo

- Start the local dev server and open http://localhost:5173 (default Vite port).

## Features

- Static feed layout and sample posts (data comes from `data.js`).
- Minimal interactive UI handled in `index.js`.
- Responsive-ish layout with the styles in `index.css`.
- Built with Vite for fast local development and a small production build.

## Requirements

- Node.js (v14+ recommended)
- npm (or any npm-compatible client)

## Install & run

From the project root:

```bash
npm install
npm run dev    # start Vite dev server
```

To create a production build and preview it locally:

```bash
npm run build
npm run preview
```

## Project structure

- `index.html` — main HTML file
- `index.css` — project styles
- `index.js` — main JavaScript entry (DOM behavior, event handlers)
- `data.js` — sample data used to populate the feed
- `images/` — project images and icons
- `package.json` — project metadata and npm scripts
- `vite.config.js` — Vite configuration (minimal)

## npm scripts

This project includes the following convenience scripts (see `package.json`):

- `npm run dev` — start the Vite development server
- `npm run build` — build static assets for production
- `npm run preview` — locally preview the production build

## Development notes

- The project is intentionally small and un-opinionated: no frameworks, no build-step complexity beyond Vite.
- Data is loaded from `data.js` for simplicity. Replace or extend this module if you want to test different feed contents.
- Styles are in a single `index.css` file — feel free to refactor into components or add a preprocessor.

## Contributing

This is a learning/demo project. If you want to contribute:

1. Fork the repo
2. Create a feature branch
3. Open a pull request with a short description of changes

Keep changes small and focused (UI improvements, accessibility, small bug fixes, or refactors).

## License

This project is provided under the MIT License. See `LICENSE` for details (if you add one).

## Acknowledgements

- Inspired by the Scrimba front-end path exercise referenced in the project metadata.

---

If you'd like, I can also:

- add a small `LICENSE` file (MIT) and commit it,
- add a short `CONTRIBUTING.md` template,
- or wire up a tiny test (Jest / vitest) to validate that `data.js` exports the expected structure.

Let me know which (if any) extras you want and I'll add them.