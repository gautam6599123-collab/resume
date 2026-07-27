# Personal Resume

> A version-controlled repository for my professional resume, typeset in LaTeX.

## Overview

This repository contains the LaTeX source code for my resume. Using LaTeX ensures precise typesetting, version control tracking for career updates, and a clean, ATS-friendly PDF output. 

## Prerequisites

To compile this resume locally, you will need a LaTeX distribution installed on your system:

* **Windows:** [MiKTeX](https://miktex.org/) or [TeX Live](https://tug.org/texlive/)
* **macOS:** [MacTeX](https://tug.org/mactex/)
* **Linux:** `texlive-full` (available via your package manager)

Alternatively, you can upload the source files to a cloud-based editor like [Overleaf](https://www.overleaf.com/) to compile it without installing anything locally.

## Compilation

To generate the PDF from the command line, navigate to the repository directory and run your preferred LaTeX compiler. `pdflatex`, `xelatex`, or `lualatex` are the most common options. 

Using `pdflatex`:

```bash
pdflatex resume.tex
