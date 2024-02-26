## Latex TikZ Figures

To include the latex TikZ figures in your slides, do the following:

1. Create the figure in pdf using a tex file with TikZ code. Once the tex file is ready you can run from terminal

```bash 
pdflatex file.tex
```

```bash 
lualatex file.tex
```

1. Once the pdf is greated, use `imagemagick` to convert it to JPEG. In the terminal, run 

```bash
convert -density 600 file.pdf file.png
```

Note: `-density 600` can be adjusted to improve image quality. It stand for dots per inch (dpi).