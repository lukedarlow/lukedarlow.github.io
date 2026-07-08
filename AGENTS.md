# Repository Instructions

This is a static personal website hosted from the repository root.

## Project Shape

- Main page: `index.html`
- Styles: `assets/css/main.css`
- Sass source: `assets/sass/main.scss` and `assets/sass/libs/`
- JavaScript: `assets/js/`
- Media and images: `images/`
- Downloadable PDFs and webfonts: `assets/`

The site is based on the HTML5 UP "Read Only" template. Preserve the existing template structure unless a requested change clearly needs broader restructuring.

## Working Guidelines

- Keep changes scoped and minimal. This is a simple static site, not an app framework.
- Prefer editing `index.html` for content changes.
- For styling changes, update Sass source when practical and keep `assets/css/main.css` in sync if the generated CSS is what the site serves.
- Do not rename or move image, PDF, font, CSS, or JavaScript assets unless every reference is updated.
- Use relative paths so the site continues to work on GitHub Pages.
- Avoid adding new build tooling or package managers unless a task explicitly requires it.
- Keep generated/vendor files such as minified libraries and webfonts unchanged unless the request is specifically about those assets.

## Verification

- For markup/content changes, inspect the affected section in `index.html` and run a lightweight local preview when visual layout matters.
- A simple preview command is:

```sh
python3 -m http.server 8000
```

- There is no project test suite or package install step by default.
