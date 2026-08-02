# Reetesh Mukul

Personal resume website and modular LaTeX resume source.

## Website

`index.html` is the GitHub Pages entry point. The same static site is mirrored in `docs/` for repositories configured to publish from that folder. The site presents the research resume as a webpage and links to `Reetesh_Mukul_Resume.pdf` for download.

## Resume Source

The current resume variants share content from `resume/templates/content.tex`:

- `01-executive.tex`
- `02-research.tex`
- `03-technical.tex`

Build a variant from `resume/templates`:

```sh
latexmk -lualatex -interaction=nonstopmode 02-research.tex
```

The legacy YAAC source remains in `resume/resume.tex` for reference.
