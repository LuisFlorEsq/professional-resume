# Luis Antonio Flores Esquivel - Professional CV

This repository contains the LaTeX source code for my professional curriculum vitae.<br>
It is designed to be ATS-friendly, modular, and easy to maintain using Git.

## Tech Stack
* **Language:** LaTeX
* **Compiler:** `latexmk` (via pdfLaTeX)
* **Editor:** TeXstudio
* **Packages:** `paracol`, `titlesec`, `hyperref`, `fontawesome5`

## How to Compile

Since this project uses `latexmk`, all cross-references, bibliographies, and formatting passes are handled automatically.

### Using the Command Line
Run the following command in the root directory:
```bash
latexmk -pdf cv_luis_flores.tex
