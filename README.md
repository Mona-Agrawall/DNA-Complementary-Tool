<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050d14,50:0a2a1a,100:050d14&height=180&section=header&text=🧬%20DNA%20Complementary%20Tool&fontSize=38&fontColor=00ff9d&fontAlignY=42&desc=Generate%20%E2%80%A2%20Visualize%20%E2%80%A2%20Export%20DNA%20Sequences&descAlignY=62&descColor=4a7a9b&animation=fadeIn" />

<br>

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-00ff9d?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-00e5ff?style=for-the-badge)

<br>

> A sleek, front-end web application that generates complementary DNA strands,  
> visualizes base-pair bonding, and lets you export your results — all in the browser.

<br>

**[🔬 Live Demo](#)** &nbsp;·&nbsp; **[🐛 Report a Bug](https://github.com/Mona-Agrawall/DNA-Complementary-Tool/issues)** &nbsp;·&nbsp; **[✨ Request a Feature](https://github.com/Mona-Agrawall/DNA-Complementary-Tool/issues)**

</div>

---

## 📸 Preview

<div align="center">
<img width="1271" alt="DNA Complementary Tool Screenshot" src="https://github.com/user-attachments/assets/12796095-c8f4-4175-8496-3a90bf65103f" style="border-radius: 12px;" />
</div>

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔬 **Instant Complement Generation** | Enter any DNA strand and get its complementary sequence in real-time using A↔T and C↔G base-pairing rules |
| 🎨 **Base-Pair Visualization** | Color-coded display of each base (A, T, C, G) with strand alignment and connector indicators |
| ✅ **Live Sequence Validation** | Real-time feedback as you type — flags invalid characters before submission |
| 📋 **Record Management** | Save, view, and delete multiple entries in a clean tabular format |
| 📥 **CSV Export** | Download all your records as a `.csv` file for use in Excel or other tools |
| 🎯 **Keyboard Shortcut** | Press `Enter` to generate instantly — no need to click |
| 📱 **Fully Responsive** | Works seamlessly on desktop, tablet, and mobile |

---

## 🧬 How It Works

The tool applies **Chargaff's base-pairing rules** to every nucleotide in the input sequence:

```
5′ → A  T  C  G  G  C  T  A → 3′
     |  |  |  |  |  |  |  |
3′ ← T  A  G  C  C  G  A  T ← 5′
```

| Input Base | Complementary Base |
|:---:|:---:|
| **A** (Adenine) | **T** (Thymine) |
| **T** (Thymine) | **A** (Adenine) |
| **C** (Cytosine) | **G** (Guanine) |
| **G** (Guanine) | **C** (Cytosine) |

---

## 🚀 Getting Started

### Prerequisites
No installations required. This is a pure front-end application — just a browser.

### Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/Mona-Agrawall/DNA-Complementary-Tool.git

# 2. Navigate to the project folder
cd DNA-Complementary-Tool

# 3. Open in your browser
open index.html
# or just double-click index.html in your file explorer
```

### Usage

1. **Enter** a sample number, your name, and a DNA strand (e.g. `ATCGGCTA`)
2. **Click** `Generate & Save` or press **Enter**
3. **View** the color-coded base-pair visualization and the complementary strand
4. **Export** all records to CSV using the Export button
5. **Delete** individual entries or clear all records at once

---

## 🛠️ Tech Stack

```yaml
Frontend : HTML5, CSS3, Vanilla JavaScript
Fonts    : JetBrains Mono (Share Tech Mono), Exo 2
Icons    : Unicode Emoji
Hosting  : Any static host (GitHub Pages, Netlify, Vercel)
```

> **Note:** This project is entirely client-side — no backend, no dependencies, no build step.

---

## 🗂️ Project Structure

```
DNA-Complementary-Tool/
│
├── index.html        # Main application (self-contained)
└── README.md         # Project documentation
```

---

## 🔮 Future Enhancements

- [ ] **RNA Transcription** — Convert DNA to its mRNA transcript (T → U)
- [ ] **Reverse Complement** — Generate the reverse complementary strand
- [ ] **GC Content Calculator** — Show the GC% of any input sequence
- [ ] **Sequence Alignment** — Compare two DNA sequences side by side
- [ ] **Dark / Light Theme Toggle** — User-selectable colour scheme
- [ ] **Persistent Storage** — Optional save-to-browser with localStorage toggle

---

## 🤝 Contributing

Contributions are welcome and appreciated!

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/your-feature-name

# 3. Commit your changes
git commit -m "feat: add your feature description"

# 4. Push to your branch
git push origin feature/your-feature-name

# 5. Open a Pull Request
```

Please make sure your code is clean and well-commented. Bug reports and feature suggestions can be submitted via [Issues](https://github.com/Mona-Agrawall/DNA-Complementary-Tool/issues).

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

Made with ❤️ by **[Mona Agrawal](https://github.com/Mona-Agrawall)**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050d14,50:0a2a1a,100:050d14&height=100&section=footer&animation=fadeIn" />

</div>
