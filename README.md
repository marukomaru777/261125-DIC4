# Context-Aware Restaurant Recommendation with Taichung Bus Accessibility

考量臺中公車交通便利性的情境感知餐廳推薦 — IEEE conference paper (LaTeX source).

## Links

- **Overleaf project:** https://www.overleaf.com/project/6b06cf5c01fce37f523aa598/share#5f8b32637417f7586e5b1aa1d092a733d52a61ae05ce1d4c
- **PDF:** [`ieee_latex/261125_DIC4.pdf`](ieee_latex/261125_DIC4.pdf)

## Files

```
ieee_paper.tex        # main paper (IEEEtran, conference)
bib/ieee_paper.bib    # references
ieee_latex/261125_DIC4.pdf  # compiled PDF
```

## Build

Requires `IEEEtran.cls` / `IEEEtran.bst` and the `CJK` package (included in TeX Live / MacTeX / Overleaf).

```bash
pdflatex ieee_paper
bibtex ieee_paper
pdflatex ieee_paper
pdflatex ieee_paper
```

On Overleaf: set **Compiler** to pdfLaTeX and **Main document** to `ieee_paper.tex`.
