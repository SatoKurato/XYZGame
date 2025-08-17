# XYZGame

Static site for XYZ Game directory. Pages include `XYZ.html` (landing), category pages and individual game pages.

Deployed via GitHub Actions to GitHub Pages. Workflow publishes site to `gh-pages` branch when you push to `main`.

How to use locally:

1. Open `f:\003\Hub` in VS Code.
2. Run Live Server extension or use Python/Node simple server:
   - PowerShell: `Set-Location 'F:\003\Hub'; python -m http.server 8000` or
   - PowerShell: `Set-Location 'F:\003\Hub'; npx http-server . -p 8000`

3. Update `search-index.json` when you add pages.
