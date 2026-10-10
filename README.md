# Margin PDF Editor

A PDF editor that runs entirely in your web browser. Your files are never uploaded anywhere.

## Features

- **Annotate:** add text, draw freehand, highlight, and add boxes, ellipses and lines
- **Sign:** draw a signature and place it anywhere on a page
- **Images:** place PNG or JPEG images on a page, then move and resize them
- **Fill forms:** type into fillable PDF form fields and tick their checkboxes
- **Edit existing text:** click a line of the PDF's text to cover it and type a replacement
- **Whiteout:** hide anything on a page
- **Pages:** reorder, rotate, delete and insert blank pages, or merge in another PDF
- **Undo and redo** for every change

## How to use

Open `index.html` in a browser, or visit the GitHub Pages link if it's enabled for this repository.

1. Click **Open** to load a PDF (or drag one onto the window). Click **Merge PDF** to add another file's pages to the end.
2. Pick a tool from the toolbar and click or drag on the page.
3. Use **Select** to move items. Drag the corner square to resize, and press Delete to remove.
4. Click **Download PDF** to save the edited file.

## Notes

- **Edit text** covers the original text with white and adds new text on top. The original words are still in the file underneath.
- **Form answers** are printed onto the page when you download, so the downloaded file is no longer fillable.
- **Added text** uses the standard PDF fonts (Helvetica, Times, Courier). Characters outside those fonts, including many non-Latin scripts, appear as "?".
- **Password-protected PDFs** aren't supported.

## Built with

- [PDF.js](https://mozilla.github.io/pdf.js/) for rendering
- [pdf-lib](https://pdf-lib.js.org/) for writing the edited PDF

Both are loaded from cdnjs, so the page needs an internet connection.
