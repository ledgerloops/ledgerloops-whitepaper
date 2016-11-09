# whitepaper
LaTeX source of https://ledgerloops.com/doc/whitepaper.pdf

# Build
```bash
$ latex whitepaper.tex
$ bibtex whitepaper.tex
$ latex whitepaper.tex
$ latex whitepaper.tex
$ dvipdf whitepaper.dvi
$ # Assuming you have https://github.com/ledgerloops/ledgerloops.com checked out next to ledgerloops-whitepaper:
$ cp whitepaper.pdf ../ledgerloops.com/doc/
