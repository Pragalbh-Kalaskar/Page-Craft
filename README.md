# 📑 PageCraft

**Extract. Unlock. Preview.**

A free, browser-based PDF page extractor. Upload a large PDF, pick the pages you need, arrange them in your preferred order, and download a new PDF. Everything runs locally, so your files are never uploaded anywhere.

## ✨ Features

- 📂 Handles large, multi-page PDFs (drag & drop or click to upload)
- 🔐 Password-protected PDFs supported, with a built-in unlock prompt
- 🔢 Flexible page selection such as `1-5, 8, 12-20`
- 👁 Output preview showing only your selected pages
- 🖱 Drag-and-drop reordering, plus remove, sort, reverse and enlarge options
- 🔒 100% private: no servers, no uploads, no tracking
- ⚡ Single HTML file with no installation or build step

## 🚀 Usage

1. Download `pagecraft.html` and open it in any modern browser (Chrome, Edge, Firefox).
2. Upload your PDF and enter the page numbers you want.
3. Click **Show Output Preview** and rearrange the pages if needed.
4. Click **Extract & Download PDF**.

## 🛠 Built with

- [pdf-lib](https://pdf-lib.js.org/) for building the output PDF
- [PDF.js](https://mozilla.github.io/pdf.js/) for rendering previews and opening protected files

## 🔒 Privacy

All processing happens inside your browser. Your PDF is never sent to any server. An internet connection is only needed to load the two libraries above.

## 📝 Note

Pages from unprotected PDFs are extracted losslessly, keeping text and quality intact. For password-protected PDFs, selected pages are rebuilt as high-quality images, so text in the output is not selectable.
