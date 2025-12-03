# Word Search Puzzle

A click-and-drag (slice) word search focused on our org’s key concepts.

## Run locally
- Open `index.html` or `wordpuzzle.html` in your browser, or
- `python3 -m http.server 8000` then visit http://localhost:8000/wordpuzzle.html

## Deploy to GitHub Pages
1. Create a new repo and add these two files: `index.html` and `wordpuzzle.html`.
2. Commit and push to the `main` branch.
3. In GitHub: Settings → Pages → Build and deployment → Source: `Deploy from a branch`. Branch: `main`, Folder: `/ (root)`.
4. Save. Your site will be available at `https://<your-username>.github.io/<repo-name>/wordpuzzle.html` (and `index.html` for the root).

If you prefer a `docs/` setup, move `index.html` and `wordpuzzle.html` into a `docs` folder and select `docs/` as the Pages folder.
