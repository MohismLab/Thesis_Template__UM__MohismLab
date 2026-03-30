# UM Thesis LaTeX Template

This repository is a clean LaTeX thesis template for MohismLab.

The University of Macau, faculty, programme, academic year, and supervisor information are kept in the template. Personal information, thesis title, abstract, and main thesis content were removed and replaced with placeholders.

## Before You Start

Please update these files first:

1. `thesis.tex`
   This is the main file. Check the `\input{sections/...}` lines and keep the sections you need.
2. `sections/cover.tex`
   Add your thesis title and your name.
3. `sections/title.tex`
   Add your thesis title, name, and student ID.
4. `sections/abstract.tex`
   Write your own abstract.
5. `sections/main_text.tex`
   Replace the sample chapter structure with your own thesis content.
6. `bib/mybib.bib`
   Add your own references.
7. `sections/list_of_tables_and_figures.tex`
   Update the abbreviation list if needed.
8. `figures/`
   Add your figures to this folder and reference them in your thesis.

## How to Build

Run these commands in the project folder:

```bash
xelatex thesis.tex
bibtex thesis
xelatex thesis.tex
xelatex thesis.tex
```

## Notes

- The main file is `thesis.tex`.
- The university logo is kept in the `figures/` folder.
- Old thesis text, personal information, and compiled PDF files were removed.
- Temporary LaTeX files and generated PDF files are ignored by `.gitignore`.

## Suggested Workflow

1. Fill in your personal information.
2. Write your abstract.
3. Replace the sample chapters with your own content.
4. Add your figures, tables, and references.
5. Compile the thesis and check the format.
