# Lab Report Template

This is a ready-to-use LaTeX template for **IOE Thapathali Campus DOECE Lab Reports**.

## Quick Start

1. Open `main.tex` in Overleaf **or** your local LaTeX environment.
2. Replace the placeholders in frontmatter:
   - Title
   - Name / Roll No
   - Experiment details
3. Edit sections inside the `sections/` folder.
4. Compile to generate the PDF.

## 📁 Structure

- `main.tex` → Main file to compile
- `frontmatter/` → Frontpages for the report
- `sections/` → Contains report content (Introduction, Methodology, Results, Conclusion)
- `images/` → Place your figures here

> Additional sections can be added as per your instructor’s requirements.

## Adding Figures

1. Place images in the `images/` folder.
2. Insert in the report using:

```latex
\begin{figure}[h]
    \centering
    \includegraphics[width=\linewidth]{images/your-image.png}
    \caption{Descriptive caption here}
    \label{fig:example}
\end{figure}
```

## Importing New Sections

You can easily add new sections or chapters to your lab report without breaking the structure.

1. **Create a new `.tex` file** inside the `sections/` folder.  
   Example: `sections/discussion.tex`

2. Import this inside main.tex file.
