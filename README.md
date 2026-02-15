
# 💝 Be My Valentine? (Interactive Valentine's Day Card)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![Made with Love](https://img.shields.io/badge/Made%20with-Love-ff69b4.svg)

This is a web-based interactive Valentine's Day card, inspired by popular trends on Instagram and TikTok. This project features a "rejection-proof" confession mechanism that uses humor and interaction to leave your Valentine with no choice but to say "Yes"!

[View Live Demo Here](https://kelvin0611.github.io/Happy-Valentine-Day/) <!-- Remember to replace with your link -->

---

## ✨ Features

This project is more than just a static image; it includes many interactive details:

* **🚫 Rejection-Proof Mechanism**: When the user tries to click "No", the button randomly moves to different positions on the screen, making it elusive.
* **📈 Emotional Blackmail Zoom**: Every time "No" is clicked, the "Yes" button grows larger until it dominates the screen, practically forcing the user to click it.
* **🐶 Dynamic Meme Reactions**: Built-in GIFs of the "Line Dog" (Maltese) that switch between "crying" or "shocked" expressions based on the number of rejections.
* **🌐 Bilingual Support**: Includes a toggle for Traditional Chinese (ZH-TW) and English (EN), perfect for cross-cultural confessions.
* **⚡ Image Preloading**: Implemented a `preloadImages` function to prevent awkward blank loading screens, ensuring smooth GIF transitions.
* **📱 Responsive Design**: Fully responsive on both mobile and desktop devices, ensuring a smooth experience anywhere.

---

## 🛠️ Tech Stack

This project remains lightweight by using native Web technologies without complex frameworks:

* ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) **HTML5** - Semantic structure.
* ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) **CSS3** - Flexbox layout, transitions, responsive design.
* ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) **JavaScript (Vanilla)** - DOM manipulation, event listeners, logic handling.

---

## 🚀 Usage

### Method 1: Direct Download
1. Download the `index.html` (or `valentine_card.html`) file from this repository.
2. Open it directly in any browser (Chrome, Safari, Edge) to run.

### Method 2: Deploy to GitHub Pages (Recommended)
1. Fork this repository to your GitHub account.
2. Go to **Settings** -> **Pages** in your repository.
3. Under **Branch**, select `main` (or `master`) and click Save.
4. Wait a few minutes, and you will get a dedicated link to share with your Valentine!

---

## 🗺️ Roadmap

- [x] Basic button interaction (growth/movement)
- [x] Bilingual support
- [x] Image preloading optimization
- [ ] **Background Music**: Add controls for romantic or funny background music.
- [ ] **Custom Names**: Allow passing the partner's name via URL parameters (e.g., `?name=Baby`).
- [ ] **More Themes**: Add themes featuring cats or other characters.

---

## 🤝 Contributing

Contributions of any kind are welcome! If you have funnier GIF links or better code optimization suggestions:

1. Fork the project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## ❓ FAQ

**Q: Why does the "No" button sometimes get covered?**
A: This is by design! As the "Yes" button grows, it eventually blocks other elements, symbolizing that "your love is overflowing." Don't worry, the "No" button will still try to jump to other places.

**Q: What if the images load slowly?**
A: The latest version includes a preloading feature (`preloadImages`), which should solve most loading issues. If your internet is very slow, it is recommended to let the page load for a moment before showing it to your partner.

---


## 👤 Author

**Your Name**

* Github: [@kelvin0611](https://github.com/kelvin0611)
* Instagram: [@wkc._0611](https://instagram.com/wkc._0611)

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
"""

filename = "README.md"

try:
    with open(filename, "w", encoding="utf-8") as f:
        f.write(content)
    print(f"✅ Successfully generated {filename}")
except Exception as e:
    print(f"❌ Error generating file: {e}")
