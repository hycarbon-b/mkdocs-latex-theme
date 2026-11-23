# MkDocs LaTeX Theme

A quiet, compact reading theme inspired by a typeset mathematics book. The sidebar uses native expandable sections; the active section opens automatically. Computer Modern and MathJax load from jsDelivr; Chinese characters use the reader's installed serif fonts. If the CDN is unavailable the browser falls back to local serif fonts and formulas remain as TeX source.

## Preview

Install MkDocs and PyMdown Extensions (`pip install mkdocs pymdown-extensions`), then run `mkdocs serve` in this directory.

## Use in a project

Point `theme.custom_dir` to the `theme` directory in this repository and use `theme.name: null`. Enable `pymdownx.arithmatex` with `generic: true` and include MathJax in `extra_javascript`; see the included `mkdocs.yml` for a complete configuration. Use `$...$` for inline math and `$$...$$` for display math. MathJax and the font CDN require network access.

The example content is for preview only. This is an independent theme; it does not change the host application's current Material preview configuration.
