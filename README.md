# Developing an Organizational Health Assessment Framework

Working title: **Developing an Organizational Health Assessment Framework: Insights from Mental Health Screening Tools**

This is a standalone LaTeX/Git project for the OHA framework foundation paper. The project now uses the INCOSE conference LaTeX template structure from `wileyNJDv5_AMA(4).tex`.

## Files

- `main.tex` - INCOSE-formatted paper source.
- `references.bib` - bibliography imported from the practicum proposal project.
- `template-images/` - INCOSE template logo assets.
- `Images/` - author biography image assets.

## Build

```powershell
latexmk -pdf main.tex
```

If `biblatex` references are added, run `biber main` between LaTeX passes or let `latexmk` manage it.
