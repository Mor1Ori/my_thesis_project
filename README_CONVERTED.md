# Converted WHU Thesis Project

This project was generated from `final.docx` and `Ref.txt` with the template from `AaronComo/WHU-Bachelor-Thesis-Template`.

## Compile

```bash
latexmk -xelatex -interaction=nonstopmode -file-line-error main.tex
```

The PDF output path is `main.pdf`.

## What Was Converted

- Cover metadata was extracted from the Word cover page.
- Chapters 1 to 4 were converted into `pages/chapter1.tex` to `pages/chapter4.tex`.
- Images were exported into `figures/`.
- References in `Ref.txt` were converted into `ref/refs.bib`.
- Numeric citations like `[1]` were converted to `\cite{ref1}` style commands.

## Current Placeholders

- Chinese abstract
- English abstract
- Acknowledgements
- Appendix

These parts were empty in the source Word document, so placeholder text is kept in the LaTeX project.

## Compatibility Notes

- The copied class file was patched to use TeX Gyre fonts instead of `Times New Roman`, so the project can compile on this machine.
- The project compiles successfully, but some wide tables still produce overfull box warnings.
