# Kato Physics

Physics lecture notes, worked examples, practice questions, and reference materials.

## Lecture 1

Units, measurement systems, and vectors:

- [Lecture notes (PDF)](Lecture%201/lecture1.pdf)
- [LaTeX source](Lecture%201/lecture1.tex)

The figure images needed to compile the notes are stored alongside the source in `Lecture 1`.

## Other materials

- `Unihw/`: university physics problem sheets.
- Root-level PDF files: reference textbooks.
- `New DOCX Document.docx`: the existing Word document from the physics folder.

## Compile the lecture notes

With a LaTeX distribution installed, run these commands from the repository root:

```powershell
Set-Location 'Lecture 1'
pdflatex --interaction=nonstopmode --halt-on-error lecture1.tex
pdflatex --interaction=nonstopmode --halt-on-error lecture1.tex
```

The second pass updates the table of contents and links. Final PDFs are tracked; LaTeX intermediate files, generated previews, and temporary editor files are ignored.
