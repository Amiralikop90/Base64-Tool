# 🔐 Base64 Tool

> Free online Base64 Encoder/Decoder — convert text to Base64 and back. Supports URL-safe mode, file upload, copy, and download.

<p align="center">
  <a href="https://amiralikop90.github.io/Base64-Tool/">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Online-success?style=for-the-badge" alt="Live Demo">
  </a>
  <img src="https://img.shields.io/badge/HTML5-Single_File-orange?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT License">
  <img src="https://img.shields.io/badge/Zero-Dependencies-brightgreen?style=for-the-badge" alt="Zero Dependencies">
</p>

---

## 📖 About

**Base64 Tool** is a sleek, single-file web tool that encodes and decodes Base64 — instantly, right in your browser. Whether you're a developer debugging an API, encoding files for embedding, or just need a quick Base64 conversion, this tool gets it done in one click.

---

## ✨ Features

### 🔄 Conversion
- 📝 **Encode** — text → Base64
- 🔓 **Decode** — Base64 → text
- 🔗 **URL-safe mode** — uses `-` and `_` instead of `+` and `/`
- 🔄 **Live conversion** — updates as you type
- 📁 **File upload** — convert any file (drag & drop or click)

### 📊 Stats
- 📏 **Character count** (input & output)
- 📦 **Size in bytes/KB/MB**
- 🔄 **Live update**

### 💾 Export
- 📋 **Copy** to clipboard
- 💾 **Download** as `.txt`
- ⇅ **Swap** input/output

### 🌐 Internationalization
- 🇮🇷 Persian (فارسی) — RTL
- 🇬🇧 English — LTR
- 🇨🇳 Chinese (中文) — LTR

### 🌙 Themes
- ☁️ **Cloud White** — soft, light, airy
- 🖤 **Matte Black** — deep, flat, no glare

### ⚡ Performance
- 🚀 **Zero backend** — everything runs in your browser
- 💾 **No tracking** — your data never leaves your device
- 📱 **Fully responsive** — mobile, tablet, desktop
- ♿ **Accessible** — ARIA labels, semantic HTML
- 🔍 **SEO-optimized** — meta tags, Open Graph, Twitter Cards, JSON-LD
- 📄 **Footer with license link** — [psoa.ir/licens.html](https://psoa.ir/licens.html)

---

## 🚀 Live Demo

👉 **[https://amiralikop90.github.io/Base64-Tool/](https://amiralikop90.github.io/Base64-Tool/)**

---

## 🛠️ How to Use

1. Open the live demo
2. Choose **Encode** (text → Base64) or **Decode** (Base64 → text)
3. Type or paste your input
4. The result appears instantly (if **Live conversion** is on)
5. Click **📋 Copy** to copy the result or **💾 Download** to save it

### Upload a File
1. Click **📁 File**
2. Drag & drop or select a file
3. The Base64 representation appears in the input
4. Copy or download as needed

---

## 🎯 Use Cases

| Use Case | Description |
|----------|-------------|
| **Developers** | Encode data for APIs, JSON, or HTML |
| **Designers** | Embed images as Base64 in CSS/HTML |
| **Security** | Safely transfer binary data as text |
| **Email** | Attach files as Base64 in email bodies |
| **URLs** | Encode data for use in URLs (URL-safe mode) |
| **Debugging** | Decode Base64 strings from logs |

---

## 📦 Deploy on GitHub Pages

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Under **Source**, select `Deploy from a branch`
4. Choose **Branch:** `main` and **Folder:** `/ (root)`
5. Click **Save** — your site will be live at:
https://amiralikop90.github.io/Base64-Tool/

text

---

## 🌍 Supported Languages

| Language | Code | Direction |
|----------|------|-----------|
| 🇮🇷 Persian | `fa` | RTL |
| 🇬🇧 English | `en` | LTR |
| 🇨🇳 Chinese | `zh` | LTR |

Language can be switched from the top bar — your choice is remembered across visits via `localStorage`.

---

## 🎨 Themes

- ☁️ **Cloud White** — soft, light, airy (default)
- 🖤 **Matte Black** — deep, flat, no glare

Toggle from the top-left button. Your preference is saved automatically.

---

## 📁 Project Structure
.
├── index.html # Entire app: HTML + CSS + JS in one file
├── robots.txt # Search engine crawler rules
├── sitemap.xml # URL list for search engines
├── LICENSE # MIT License
└── README.md # This file

text

> The entire application lives inside a **single `index.html`** — no build tools, no bundlers, no `node_modules`.

---

## 🧰 Tech Stack

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties for theming
- **JavaScript (Vanilla)** — no frameworks, no libraries
- **FileReader API** — for file upload
- **Clipboard API** — for copy/paste
- **GitHub Pages** — free static hosting

---

## 🔍 SEO Features

This project ships with production-grade SEO out of the box:

- ✅ Optimized `<title>` and `<meta description>`
- ✅ `hreflang` tags for multilingual content
- ✅ Open Graph (Facebook, LinkedIn, Telegram)
- ✅ Twitter Card (`summary_large_image`)
- ✅ JSON-LD structured data (`WebApplication` schema)
- ✅ Canonical URL
- ✅ `robots.txt` and `sitemap.xml`
- ✅ Google Search Console verified
- ✅ Semantic headings
- ✅ ARIA labels for accessibility

---

## 🔒 Security

- ✅ **All processing is local** — no data sent to any server
- ✅ **No tracking** — no analytics, no cookies
- ✅ **No storage** — nothing is saved
- ✅ **Open source** — inspect the code yourself

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for new features, additional languages, or UI improvements:

1. Fork the repository
2. Create your branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

## 🔮 Planned Features

- 🎨 **Image preview** — show images decoded from Base64
- 📄 **Multiple file support** — convert multiple files at once
- 📥 **File download** — decode Base64 back to original file
- 🌐 **More languages** — Arabic, Russian, Spanish, German, French
- 📱 **PWA support** — install as a mobile app
- 📊 **Bulk conversion** — encode multiple strings at once

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

See the [LICENSE](LICENSE) file for details.

For more information, visit the license page:
👉 **[https://psoa.ir/licens.html](https://psoa.ir/licens.html)**

---

## 👤 Author

**Amirali Kamani**

- 🌐 Website: [psoa.ir](https://psoa.ir)
- 💻 GitHub: [@Amiralikop90](https://github.com/Amiralikop90)
- 📜 License page: [psoa.ir/licens.html](https://psoa.ir/licens.html)

---

<p align="center">
  Made with ❤️ — because Base64 should be one click away.
</p>
