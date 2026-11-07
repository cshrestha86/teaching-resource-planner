# Teaching Expertise & Resource Planning — GitHub Pages

This website includes:

1. **Live Demo:** `demo/index.html` — interactive synthetic dashboard.
2. **Dashboard Builder:** `builder/index.html` — standalone HTML app.
3. **Excel Template:** `templates/Module-Matrix-Demo.xlsx` — demonstration workbook.

The `assets/pc3-copyright.png` image is used on the landing page.

## Publishing

**Important: Upload the contents of this folder directly to the repository root, not the folder itself, and do not upload the ZIP as a single file.**

Expected layout in the GitHub repository:

```
index.html
.nojekyll
demo/index.html
builder/index.html
templates/Module-Matrix-Demo.xlsx
assets/pc3-copyright.png
README.md
```

On GitHub, go to **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/(root)`, and save.

For a project repository named `teaching-resource-planner`, your links will be:

- `https://USERNAME.github.io/teaching-resource-planner/`
- `https://USERNAME.github.io/teaching-resource-planner/demo/index.html`
- `https://USERNAME.github.io/teaching-resource-planner/builder/index.html`

If the landing page works but clicking a link returns **404**, confirm the exact file paths in GitHub. GitHub filenames and directories are case-sensitive. Allow Pages deployment to finish, and refresh the browser.

If a tool page loads **blank**, open browser Developer Tools → Console and check for JavaScript errors. The two HTML apps were supplied by the author and are included unchanged; working file links do not establish that their own JavaScript runs error-free in every browser.

## Data warning

All published demonstration content should be synthetic. Review the workbook and HTML content before public deployment. The Excel workbook provided is populated, not blank.
