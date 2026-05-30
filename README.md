# 🌍 UniKOD — ONE LANGUAGE. UNLIMITED POSSIBILITIES.

> *"The limit is only the person themselves."* — AcizBirKul (Kadir Çakmak)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Languages](https://img.shields.io/badge/Languages-9%2B-blueviolet)]()
[![Platform](https://img.shields.io/badge/Platform-Browser-blue)]()
[![Built with Claude](https://img.shields.io/badge/Built%20with-Claude%20Sonnet%204.6-orange)]()

**Live Demo:** https://seyyidkadir.github.io/UniKOD/  
**Language Pack Editor:** https://seyyidkadir.github.io/UniKOD/ukodlang_editor.html

---

## What is UniKOD?

UniKOD is an open-source, browser-based IDE that lets anyone write real, executable programs in their **own native language** — not English, not pseudocode, but actual programming in Turkish, Indonesian, German, French, Spanish, Urdu, Japanese, Chinese, or any language you bring to it.

No installation. No compiler. No English required.

---

## 🗣️ Supported Languages (Built-in)

| Flag | Language | Code |
|------|----------|------|
| 🇹🇷 | Türkçe (Turkish) | `tr` |
| 🇬🇧 | English | `en` |
| 🇩🇪 | Deutsch (German) | `de` |
| 🇫🇷 | Français (French) | `fr` |
| 🇪🇸 | Español (Spanish) | `es` |
| 🇮🇩 | Bahasa Indonesia | `id` |

**Loadable via `.ukodlang` packs:**

| Flag | Language | Code |
|------|----------|------|
| 🇵🇰 | اردو (Urdu) | `ur` |
| 🇯🇵 | 日本語 (Japanese) | `ja` |
| 🇨🇳 | 中文 (Chinese) | `zh` |

---

## ✨ Features

### 🖥️ Full IDE in the Browser
- Code editor with syntax highlighting
- Real-time debugger with breakpoints
- Console, variable inspector, help panel
- Solution Explorer with module & resource management

### 🌐 Universal Language Engine
- Write programs in any supported language
- Real-time hybrid translation between languages
- **Directive system** (`#TR`, `#EN`, `#UR`...) — different modules of the same program can be written in different languages
- Language-aware autocomplete
- Localized error messages

### 🎨 GUI System
- Windows, buttons, labels, text inputs, checkboxes, radio buttons
- Canvas 2D drawing (shapes, images, text)
- Canvas 3D (cubes, spheres, cylinders, custom geometry)
- Sound engine (`Ses` / `Sound` / `Suara`...)
- Timer, progress bar, slider, list, web view

### 📦 Library System (`.tklib`)
- Write reusable libraries in any language
- Import with `#USE` directive
- Libraries can be written in a different language than the main program

### 🌍 Language Pack System (`.ukodlang`)
- Create new language packs with the visual editor
- Dictionary (keywords) + UI strings in one file
- LTR/RTL support
- Load any `.ukodlang` file at runtime

---

## 🚀 Quick Start

Open https://seyyidkadir.github.io/UniKOD/ in your browser — no installation needed.

**Example (Turkish):**
```
Dugme btn;
btn.yazi = "Merhaba Dünya!";
btn.tiklaninca = Fonksiyon()
  Mesaj("Merhaba!");
FonksiyonBitti

Pencere pen;
pen.Ekle(btn);
pen.Goster();
```

**Example (Indonesian):**
```
Tombol btn;
btn.teks = "Halo Dunia!";
btn.diklik = Fungsi()
  Pesan("Halo!");
FungsiBerakhir

Jendela pen;
pen.Tambah(btn);
pen.Tampilkan();
```

**Example (German):**
```
Schaltflaeche btn;
btn.text = "Hallo Welt!";
btn.angeklickt = Funktion()
  Nachricht("Hallo!");
FunktionEnde

Fenster pen;
pen.Hinzufuegen(btn);
pen.Anzeigen();
```

---

## 🧩 Language Pack Editor

Want to add a new language? Use the visual editor:

👉 https://seyyidkadir.github.io/UniKOD/ukodlang_editor.html

- Available in 6 UI languages (EN, TR, DE, FR, ES, ID)
- Fill in keyword translations and UI strings
- Export as `.ukodlang` file
- Load into UniKOD at runtime

---

## 📁 Repository Structure

```
UniKOD/
├── index.html              # Main IDE
├── ukodlang_editor.html    # Language pack editor
└── README.md
```

---

## 🧠 The Story Behind UniKOD

UniKOD started as a simple C# interpreter written in 2012. A few months ago, its creator handed that old code to Claude and asked: *"How could this be better?"*

That question turned into TurkishKOD. TurkishKOD turned into a conversation about potential. That conversation turned into UniKOD — because English is a universal language, but there are still billions of people with brilliant ideas who don't speak it.

The vision: **programming should be accessible to every human being, regardless of which language they were born speaking.**

UniKOD was built entirely through human–AI collaboration between Kadir Çakmak and Claude Sonnet 4.6. Every architectural decision, every bug fixed, every feature designed — made together.

---

## 👤 Creator

**AcizBirKul (Kadir Çakmak)**  
High school computer technician (class valedictorian) · University web programming student · Solo developer

> *"I am an ordinary person with an extraordinary vision."*

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 🤝 Contributing

Want to add a new language?
1. Open the [Language Pack Editor](https://seyyidkadir.github.io/UniKOD/ukodlang_editor.html)
2. Fill in the keyword translations
3. Export your `.ukodlang` file
4. Open an issue or pull request on this repository

All languages welcome. All people welcome.

---

*UniKOD v1.0 — Built with ❤️ and Claude Sonnet 4.6*
