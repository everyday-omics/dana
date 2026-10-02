# Hebrew PDF Copy

Fixes scrambled Hebrew and English text copied from PDF files, such as clinical summaries viewed in Acrobat.

Open `pdfcopy.html` in a browser (Edge or Chrome), then either:

- **Paste a screenshot** of the paragraph (Win+Shift+S, then Ctrl+V). The text is read with built-in optical character recognition.
- **Load or drag the PDF file**, then mark the area you want. The text is read directly from the file, so this is the most accurate option.

The corrected text is shown right to left and can be edited and copied. Words the tool is unsure of are shown in red.

## Privacy

Everything runs inside the browser on your computer. Nothing is uploaded or saved, no network access is needed, and no language models (LLMs) are used. The file works offline once downloaded.

## Built with

- [Tesseract.js](https://github.com/naptha/tesseract.js) with the Hebrew and English `best_int` models, embedded in the file (Apache License 2.0)
- [pdf.js](https://github.com/mozilla/pdf.js) by Mozilla, embedded in the file (Apache License 2.0)

## License

This project is licensed under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/): free to use, share and adapt for non-commercial purposes, with attribution. Commercial use is not permitted. See [LICENSE](LICENSE).

The embedded third-party components keep their own Apache License 2.0; see [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).

Created by Dr. Tom Rabinowitz @ Dana-Dwek Children's Hospital, Tel Aviv Sourasky University Medical Center
