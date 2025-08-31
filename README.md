# Image Resizer App

---



````markdown
# 🖼️ Image Resizer App

A Python desktop application (Tkinter + Pillow) for quickly **resizing, previewing, and exporting images** for web and app use.  
It was built to streamline my personal workflow when preparing images and icons for my website, but it can also be useful to designers, developers, and anyone who needs **fast responsive image prep**.

---

## ✨ Features

- **Quick Resize**  
  - Choose width presets (Icon, Mobile, Tablet, Desktop, HD, etc.)  
  - Maintain aspect ratio or force orientation (16:9, 9:16, square)  
  - Save in multiple formats: `.png`, `.jpg`, `.webp`, `.ico`, `.gif`

- **Exact Presets**  
  - One-click exports for common sizes:
    - Favicons (`16×16`, `32×32`, `64×64`, etc.)
    - PWA icons (`192×192`, `512×512`)
    - Social / Open Graph images (`1200×630`, `1600×900`, etc.)
    - Avatars, hero banners, thumbnails

- **Live Preview**  
  - See how your image would look on different devices:
    - 📱 Phone (360×800)
    - 📲 Tablet (768×1024)
    - 🖥️ Desktop (1920×1080)  
  - Device Pixel Ratio (1×, 2×, 3×) sharpness checks

- **Advanced Controls**  
  - JPEG / WebP quality sliders  
  - Progressive JPEG support  
  - Keep/remove EXIF metadata  
  - Auto-orient from EXIF  
  - Optional sharpening after downscale  
  - Custom DPI for print

- **Export Options**  
  - 💾 Save resized image  
  - 📦 Export **responsive bundle** (`srcset` HTML snippet auto-copied to clipboard)  
  - 🗂 Batch export multiple images at once  
  - ⭐ Export **favicon pack** (`.ico` + PNG + `<link>` tags for HTML)

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Tkinter** → for GUI
- **Pillow (PIL)** → for image processing
- **ttk / Tk themed widgets** → for clean UI

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/neilsoncaleb/Image-Resizer-App.git
cd Image-Resizer-App
````

Install dependencies:

```bash
pip install pillow
```

Run the app:

```bash
python src/main.py
```

---

## 💻 Windows Executable

For convenience, a packaged `.exe` is available under **[Releases](https://github.com/neilsoncaleb/Image-Resizer-App/releases)**.
This allows you to run the app without installing Python.

---

## 📂 Repository Structure

```
Image-Resizer-App/
├── README.md          # Project documentation
├── src/               # Python source code
│   └── main.py        # Tkinter GUI application
└── dist/              # Compiled executable (.exe) for Windows
```

---

## 📷 Screenshots (optional)

*(You can add some screenshots of the GUI here to show the preview tabs, device frames, etc.)*

---

## 🤝 Contributing

This tool was made for my own workflow, but contributions and improvements are welcome!
Feel free to fork, open an issue, or submit a pull request.

---

## 📜 License

MIT License © 2025 [CJ Neilson](https://github.com/neilsoncaleb)

```

---

👉 If you copy this into your `README.md`, GitHub will auto-render it nicely. You can later add **screenshots** of the GUI (very valuable for attracting attention).

Would you like me to also draft a **GitHub Release guide** (so you can upload your `.exe` there and make the “Download EXE” button work right away)?
```


