## UOttawa Masters Thesis Latex Template

## Requires
- pdflatex
- inkscape (if you want to support svgs)

## Usage

*Change directories into the SRC directory*

```
cd src
```

*Compile latex*
```
pdflatex --shell-escape index.tex
```

*Generate the references from bibtex*
```
 bibtex index.aux
```

*Compile latex again*
```
pdflatex --shell-escape index.tex
```

> Shell escape ensures any compilation of svg images (since this template supports importing using the svg tag instead of the includegraphics tag) get generated correctly.
