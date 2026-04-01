# Local LaTeX Setup Guide

## 1. Install LaTeX

### Linux (TeX Live)

    sudo apt install texlive-full

### Windows

    Install MiKTeX: https://miktex.org/download

### macOS

    Install MacTeX: https://tug.org/mactex/

## 2. Compile the Project

Navigate to template folder:

    cd lab-report

Run:

    latexmk -pdf -g main.tex
    or,
    latexmk -pdf -pvc -interaction=nonstopmode "main.tex"


## 3. Clean Build Files

    latexmk -c

## ❗ Notes

- Make sure `latexmk` is installed
- If errors occur, try running `pdflatex` twice
