# BidiFix

Fixes scrambled Hebrew and English text copied from PDF files, such as clinical summaries viewed in Acrobat.

Open `bidifix.html` in a browser (Edge or Chrome), then either:

- **Paste a screenshot** of the paragraph (Win+Shift+S, then Ctrl+V). The text is read with built-in optical character recognition.
- **Load or drag the PDF file**, then mark the area you want. The text is read directly from the file, so this is the most accurate option.

The corrected text is shown right to left and can be edited and copied. Words the tool is unsure of are shown in red.

## Privacy

Everything runs inside the browser on your computer. Nothing is uploaded or saved, no network access is needed, and no language models (LLMs) are used. The file works offline once downloaded.

## Built with

- [Tesseract.js](https://github.com/naptha/tesseract.js) with the Hebrew and English `best_int` models, embedded in the file (Apache License 2.0)
- [pdf.js](https://github.com/mozilla/pdf.js) by Mozilla, embedded in the file (Apache License 2.0)

Created by Dr. Tom Rabinowitz @ Tel Aviv Sourasky University Medical Center
