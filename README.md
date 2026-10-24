# Sujee Rubio, Mechanical Engineering Portfolio

Live site: https://sujeerubio.github.io/portfolio/

A single-page static site (no build step). Each project has its own view, linked as `#supersonic`, `#rocket`, `#shaft`, `#brake`, `#wind-tunnel`, `#understand` and `#handhug`.

## Structure
- `index.html`: the whole site (styles and script included)
- `assets/img/<project>/`: figures, renders and video
- `assets/files/SujeeRubio_Resume.pdf`: résumé linked from the site

## Publishing with GitHub Pages
1. Create a public repository named `portfolio` on github.com/sujeerubio.
2. Upload everything in this folder: **Add file → Upload files**, then drag in `index.html`, `README.md` and the `assets` folder, and commit.
3. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, then branch `main` and folder `/ (root)`, and save.
4. After about a minute the site is live at `https://sujeerubio.github.io/portfolio/`.

## Updating
- To replace the résumé, upload a new `assets/files/SujeeRubio_Resume.pdf` with the same name.
- To change text, edit `index.html` on GitHub (pencil icon) and commit.
