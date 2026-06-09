# QR Code Generator

**Convert any text or URL into a scannable QR code in seconds — with a polished, responsive interface.**

---

## 🚀 Try it now

Open any version in your browser:
- **Final version (best):** Open `12-polished/index.html`
- **Or explore earlier versions** to see the design progression from basic HTML to a complete, polished app

All versions work offline and require zero setup.

---

## ✨ Features

- **Instant QR generation** — Type text or a URL and get a scannable QR code immediately
- **Customizable size** — Choose between 220×220, 320×320, or 420×420 pixels
- **Color options** — Pick from multiple color schemes (black, indigo, teal, crimson)
- **Copy to clipboard** — One-click text copying for easy sharing
- **Download as PNG** — Save your QR code for offline use
- **Mobile-friendly** — Fully responsive design works on all devices
- **No dependencies** — Pure HTML, CSS, and JavaScript — runs anywhere

---

## 🎯 Quick start

1. Open `12-polished/index.html` in your browser
2. Type or paste any text, URL, or link
3. Click "Generate QR Code"
4. Copy the content or download the image

That's it. No install, no build, no commands.

---

## 📚 Progressive learning versions

This project includes **12 versions**, each building on the last:

| Version | Focus | What's new |
|---------|-------|-----------|
| 1 | Basic HTML | Simple form structure |
| 2 | HTML upgrade | Improved form layout and preview area |
| 3 | Styling | First CSS styling and cards |
| 4 | Script | JavaScript interaction and live preview |
| 5 | HTML polish | Better semantics and structure |
| 6 | Better style | Modern gradients and spacing |
| 7 | Script upgrade | Validation and better feedback |
| 8 | **Functional** | First working QR generation |
| 9 | Modern UI | Copy and download buttons |
| 10 | Responsive | Mobile-friendly grid layout |
| 11 | Full features | Size and color customization |
| 12 | **Polished** | Final UX, animations, and theme-ready |

Each folder is a standalone, complete version. Open any `index.html` to see that stage.

---

## 🛠 How it works

The generator uses the **QR Server API** (`api.qrserver.com`) to encode your input into a scannable QR code image. Here's the flow:

1. **User input** — Text or URL from the form
2. **Size selection** — User picks dimensions (220–420 pixels)
3. **Color pick** — User chooses from preset colors
4. **API call** — JavaScript builds a URL: `https://api.qrserver.com/v1/create-qr-code/?size=320x320&color=1e3a8a&data=...`
5. **Image display** — The API returns a PNG that's displayed instantly
6. **Download/share** — User can copy text or download the PNG

No backend needed. No installation. Just vanilla JavaScript and a free API.

---

## 💡 Why 12 versions?

This project demonstrates **progressive enhancement** — starting with basic HTML and gradually adding styling, interactivity, and polish. It's a learning resource to see how a simple idea grows into a polished product, one step at a time.

---

## 📄 License

Open source. Use, modify, and share freely.

---

**Ready to generate?** Open `12-polished/index.html` now.
