# QR Code Generator

Convert any text or URL into a scannable QR code. No install, no build step, no backend.

---

## Try it

Open `index.html` in your browser. That's it.

---

## What it does

- Type or paste any text or URL and get a QR code immediately
- Choose from three sizes: 220x220, 320x320, or 420x420 pixels
- Pick a color scheme: black, indigo, teal, or crimson
- Copy the input text to clipboard with one click
- Download the QR code as a PNG

Works on mobile. No dependencies -- pure HTML, CSS, and JavaScript.

---

## Quick start

1. Open `index.html` in your browser
2. Type or paste any text or URL
3. Click "Generate QR Code"
4. Copy or download

---

## How it works

The generator calls the QR Server API (`api.qrserver.com`), which returns a PNG image. JavaScript builds the request URL with your input, size, and color choice, then displays the result. No server-side code involved.

---

## License

Open source. Use, modify, share.
