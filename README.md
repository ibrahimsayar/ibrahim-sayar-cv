# CV - Ibrahim Sayar

Professional CV

## Build

```bash
pdflatex cv.tex
```

Requires a LaTeX distribution with `moderncv` package (e.g., TeX Live, MiKTeX, or MacTeX).

## Quick Build (Docker)

```bash
docker run --rm -v $(pwd):/doc thomasweise/texlive pdflatex cv.tex
```
