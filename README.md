# dipf-thesis-template
Template for theses or other scientific papers from DIPF.

# Usage
```
mkdir out
pdflatex -interaction=batchmode -shell-escape main
bibtex main
pdflatex -interaction=batchmode -shell-escape main
pdflatex -interaction=batchmode -shell-escape main
```
