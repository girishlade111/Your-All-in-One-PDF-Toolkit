# Your All-in-One PDF Toolkit (PDF Power Tools)

A free, privacy-first web toolkit for everyday PDF tasks — merge, split, compress, rotate, protect, and convert PDFs entirely in the browser. No uploads, no sign-up, no backend: your files never leave your device.

## Features

- **Merge PDF** — combine multiple PDFs into one
- **Split PDF** — extract selected pages into a new PDF
- **Compress PDF** — shrink file size
- **Rotate PDF** — rotate pages
- **Protect PDF** — add password protection
- **Convert to PDF** — JPG images, DOC/DOCX, XLSX, PPT/PPTX, and HTML webpages → PDF
- **Add text / annotations** — stamp text onto pages
- Dark-mode UI, drag-and-drop, fully responsive

## Tech stack

- Single self-contained `index.html` (no build step)
- [pdf-lib](https://pdf-lib.js.org/) for client-side PDF manipulation
- Tailwind CSS (CDN) for styling

## Quick start

Open `index.html` in any modern browser — that's it. No install needed.

Or serve it locally:

```bash
npx serve .
# or
python3 -m http.server 8000
```

## Privacy

All processing happens locally in the browser using pdf-lib. No file is ever uploaded to a server.

## Deploy

Deployed via GitHub Pages from the `main` branch.

## License

Free to use.

---

Built by Girish Lade — https://ladestack.in
