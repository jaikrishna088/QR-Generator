# ✦ QR Magic — Professional QR Code Generator

![QR Magic Banner](https://img.shields.io/badge/QR%20Magic-Pro%20Generator-7c3aed?style=for-the-badge&logo=qrcode&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/Backend-None%20Required-16a34a?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-ec4899?style=for-the-badge)

> **A beautiful, feature-rich QR code generator that runs 100% in the browser — no backend, no API key, no sign-up required.**

---

## 🌟 Live Demo

Simply open `qr-generator.html` in any modern browser and start generating!

> 💡 You can also deploy it instantly for free on **GitHub Pages**, **Netlify**, or **Vercel** — just upload the single HTML file.

---

## 📸 Features at a Glance

| Feature | Details |
|---|---|
| 🔗 **8 Content Types** | URL, Text, WiFi, vCard, Email, Phone, SMS, Location |
| 🎨 **Full Customisation** | Color themes, custom foreground/background pickers |
| 📐 **Size Control** | 128px to 512px with a smooth slider |
| 🛡️ **Error Correction** | 4 levels: L / M / Q / H |
| 🖼️ **Logo Overlay** | Drag & drop your brand logo onto the QR |
| 🏷️ **Custom Label** | Add a text label below the QR code |
| 🔲 **Rounded Frame** | Toggle a modern rounded container |
| ⚡ **Live Preview** | QR updates automatically as you type |
| 💾 **Export Options** | Download as PNG, SVG, or copy to clipboard |
| 🕒 **History** | Keeps your last 8 generated QR codes |
| 📱 **Fully Responsive** | Works perfectly on desktop, tablet, and mobile |

---

## 🚀 Getting Started

### Option 1 — Open directly in browser

```bash
# Clone the repository
git clone https://github.com/[repo-url]/qr-magic.git

# Navigate into the folder
cd qr-magic

# Open the file in your browser
open qr-generator.html        # macOS
start qr-generator.html       # Windows
xdg-open qr-generator.html   # Linux
```

### Option 2 — Serve locally (optional)

```bash
# Using Python
python -m http.server 8080

# Using Node.js
npx serve .
```

Then visit `http://localhost:8080` in your browser.

---

## 📁 Project Structure

```
qr-magic/
│
├── qr-generator.html     # Main application (single file, fully self-contained)
└── README.md             # You are here
```

> The entire app is a **single HTML file** — no build tools, no node_modules, no configuration needed.

---

## 🛠️ How to Use

### Step 1 — Choose your content type

Pick from 8 types using the visual selector cards:

- **🔗 Website** — Encode any URL
- **📝 Text** — Plain text, messages, coupon codes
- **📶 WiFi** — Let guests join your network instantly
- **👤 Contact (vCard)** — Share your full contact details
- **✉️ Email** — Pre-fill recipient, subject and body
- **📞 Phone** — One scan to call
- **💬 SMS** — Pre-filled text message
- **📍 Location** — GPS coordinates with a label

### Step 2 — Customise the style

- Pick a **colour theme preset** or use custom colour pickers
- Adjust the **size** from 128px to 512px
- Choose your **error correction level** (use H when adding a logo)
- Upload a **logo/icon** to overlay on the centre
- Add a **custom label** below the code
- Toggle the **rounded frame** for a modern look

### Step 3 — Download

- **PNG** — Best for print and digital use
- **SVG** — Scalable vector, perfect for high-resolution output
- **Copy** — Paste directly into any app

---

## 🎨 Colour Themes

| Theme | Dark Colour | Light Colour |
|---|---|---|
| Classic Black | `#000000` | `#ffffff` |
| Purple | `#5b21b6` | `#f5f3ff` |
| Sky Blue | `#0369a1` | `#e0f2fe` |
| Emerald | `#14532d` | `#dcfce7` |
| Orange | `#7c2d12` | `#fff7ed` |
| Pink | `#831843` | `#fdf2f8` |
| Dark Slate | `#0f172a` | `#f8fafc` |
| Amber | `#78350f` | `#fffbeb` |

You can also use the custom colour pickers for any colour combination.

---

## 🧩 Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5 / CSS3** | Structure and styling |
| **Vanilla JavaScript** | All interactivity and logic |
| **[qrcode.js](https://github.com/davidshimjs/qrcodejs)** | QR code generation (via CDN) |
| **Google Fonts — Nunito** | Typography (via CDN) |
| **HTML5 Canvas API** | Logo overlay and image export |
| **Clipboard API** | Copy to clipboard |

No npm, no build step, no framework — just open and use.

---

## 📱 QR Content Formats

### WiFi
```
WIFI:T:WPA;S:MyNetwork;P:MyPassword;;
```

### vCard
```
BEGIN:VCARD
VERSION:3.0
FN:John Doe
TEL:+1 234 567 8900
EMAIL:john@example.com
ORG:Acme Corp
END:VCARD
```

### Email
```
mailto:recipient@example.com?subject=Hello&body=Message
```

### SMS
```
sms:+1234567890?body=Hello%20there
```

### Geo Location
```
geo:40.7128,-74.0060?q=New%20York%20City
```

---

## 🔧 Customisation Tips

**Best error correction level for logos:** Use **H (30%)** — this allows up to 30% of the QR data to be obscured while still scanning correctly.

**Recommended logo size:** Keep the logo between **15–25%** of the total QR size for reliable scanning.

**Contrast matters:** Always ensure strong contrast between your foreground (dots) and background colour for reliable scanning.

**Test before printing:** Always scan your QR code on multiple devices before printing at scale.

---

## 🌐 Browser Support

| Browser | Support |
|---|---|
| Chrome 90+ | ✅ Full support |
| Firefox 88+ | ✅ Full support |
| Safari 14+ | ✅ Full support |
| Edge 90+ | ✅ Full support |
| Mobile Chrome | ✅ Full support |
| Mobile Safari | ✅ Full support |

> Note: The "Copy to clipboard" feature requires a secure context (HTTPS or localhost) in some browsers.

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute.

```
MIT License

Copyright (c) 2026 QR Magic Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 🙌 Acknowledgements

- [qrcode.js](https://github.com/davidshimjs/qrcodejs) by davidshimjs — QR code generation library
- [Google Fonts](https://fonts.google.com/specimen/Nunito) — Nunito typeface

---

## 💬 Contributing

This is an **open source project** — contributions of all kinds are welcome!

Whether you're fixing a bug, improving the UI, adding a new QR type, or improving docs — every contribution matters.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

Please open an **Issue** first for major changes so we can discuss the approach together.

---

<div align="center">

Open Source with ❤️ · Give it a ⭐ if you found it useful!

**Contributions welcome — fork it, improve it, share it.**

</div>
