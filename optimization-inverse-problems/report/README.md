# Laboratory 2 — Written Solution

This folder contains the LaTeX source and the original figures extracted from
`../lab2.ipynb`.

## Files

- `main.tex` — complete report source.
- `figures/` — the nine figures used in the report (PNG, taken directly from the
  notebook outputs).
- `main.pdf` — compiled report.

## Compiling (Overleaf or local LaTeX)

1. Upload `main.tex` and the `figures/` folder, keeping the same relative paths.
2. Set `main.tex` as the main document.
3. Compile with pdfLaTeX (default in Overleaf).

Required packages are standard and available in TeX Live / Overleaf:
`amsmath`, `amssymb`, `graphicx`, `booktabs`, `caption`, `subcaption`,
`float`, `enumitem`, `microtype`, `parskip`, `hyperref`, `geometry`, `lmodern`.

The document has no shell-escape, BibTeX, or external-file dependencies.
Overleaf's default multi-pass compilation resolves all cross-references
automatically.
