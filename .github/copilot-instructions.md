# Copilot Instructions for senai-flix-dev-js

## Project Overview
This is a simple static web project for SENAIFLIX, a movie and series showcase. The codebase is organized for clarity and separation of concerns, with dedicated folders for assets, pages, and scripts.

## Architecture & Structure
- **Pages:**
  - `home/index.html` and `detalhes-do-filme/index.html` are the main entry points for the site.
  - Each page has its own CSS file for local styles, plus a shared global stylesheet in `assets/styles/global.css`.
- **Assets:**
  - Images, icons, and videos are stored in `assets/imgs`, `assets/icons`, and `assets/videos` respectively.
- **Scripts:**
  - All JavaScript is placed in `scripts/script.js`. Currently, this file is empty; add page logic here if needed.

## Patterns & Conventions
- **HTML:**
  - Use semantic HTML5 structure. Example: `<header>`, `<main>`, `<footer>`.
  - Link local CSS first, then global CSS for shared styles.
- **CSS:**
  - Page-specific styles go in the page's folder (e.g., `home/home.css`).
  - Shared styles belong in `assets/styles/global.css`.
- **Assets:**
  - Reference images and icons using relative paths from the HTML file location.
  - Keep asset folders organized by type.

## Developer Workflow
- No build tools or frameworks are used; edit HTML/CSS/JS directly.
- No automated tests or CI/CD are present.
- To preview changes, open HTML files directly in a browser.
- No package management or external dependencies.

## Examples
- To add a new page, create a folder with `index.html` and a local CSS file, then link to global styles.
- To use an image: `<img src="../assets/imgs/Banner-BB.png" alt="Banner">`
- To add JS logic, edit `scripts/script.js` and link it in your HTML if needed.

## Key Files & Directories
- `home/`, `detalhes-do-filme/`: Main pages
- `assets/`: All static resources
- `scripts/script.js`: Place for JavaScript logic

## Additional Notes
- Keep file and folder names lowercase and descriptive.
- No backend or dynamic data; all content is static.
- If adding new conventions, document them here for future agents.
