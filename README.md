## Vilniaus university Software Engineering master's thesis LaTeX template

Template utilizes:  
- `latexmk` for running the compilation  
- `lualatex` for generating the PDF  
- `biblatex` and `biber` for bibliography  

Main font is [Palemonas](https://vlkk.lt/palemonas).

## Prerequisites

### Linux

Install Tex Live.

#### Ubuntu

Run `make ubuntu` command in this directory.

### Overleaf

Compiler has to be changed to LuaLaTeX, see: https://www.overleaf.com/learn/how-to/Changing_compiler.

### Windows

Install one of:  
- [Tex Live](https://tug.org/texlive/windows.html)  
- [MikTex](https://miktex.org/download) and `biber`

### macOS

Install [MacTex](https://tug.org/mactex).

## Generating the PDF

### Linux / macOS

Run one of:  
- `make`  
- `make pdf`  
- `latexmk -lualatex master_thesis.tex`

### Windows

Run `latexmk -lualatex master_thesis.tex`.

## Other useful commands

### Linux / macOS

- continuous recompilation on document changes: `make watch`
- approximate word count of thee thesis: `make wordcount`  
- LaTeX error check (note: generates a lot of warnings, not all of them need to be addressed): `make check`  
- remove unnecessary files (leftover from the PDF generation): `make clean`

## Thesis requirements

Lithuanian:  
- [provisions for preparing the thesis](https://mif.vu.lt/lt3/dokumentai/dokumentai/PS/2022-02-21_MSc_provisions-2022-LT.pdf)  
- [thesis structure](https://mif.vu.lt/lt3/dokumentai/dokumentai/PS/2022-02-21_MSc_thesis_structure-2022-LT.pdf)

English:  
- [provisions for preparing the thesis](https://mif.vu.lt/lt3/dokumentai/dokumentai/PS/2022-02-21_MSc_provisions-2022-EN.pdf)  
- [thesis structure](https://mif.vu.lt/lt3/dokumentai/dokumentai/PS/2022-02-21_MSc_thesis_structure-2022-EN.pdf)  
