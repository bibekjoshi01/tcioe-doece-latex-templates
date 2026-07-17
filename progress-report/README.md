# 1. Stop the running watcher with Ctrl+C

# 2. Clean generated helper files
latexmk -c main.tex

# 3. Build fresh
latexmk -pdf -interaction=nonstopmode main.tex
latexmk -pdf -pvc -interaction=nonstopmode "main.tex"