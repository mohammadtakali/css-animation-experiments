# 🧪 CSS Animation Experiments

A growing collection of small, focused **pure CSS3** experiments — each one explores a single idea: a rotating menu, a looping text slider, a 3D solar system, and more to come.

No JavaScript. No frameworks. No build step. Just HTML, CSS and a lot of curiosity. ✨

---

## 📑 Table of Contents

- [🧩 Projects](#-projects)
- [📂 Repository Structure](#-repository-structure)
- [🚀 Getting Started](#-getting-started)
- [🌐 Live Demos](#-live-demos)
- [👤 Author](#-author)

---

## 🧩 Projects

| # | Project | What it does | Key techniques |
|---|---------|--------------|----------------|
| 1️⃣ | **[Hamburger Menu](./hamburger-menu)** 🍔 | A quarter-circle hamburger button in the corner. Hover and it rotates, the page tilts away, and menu items slide in one by one. | `transform`, `transform-origin`, sibling selector `~`, staggered `transition-delay`, custom icon font |
| 2️⃣ | **[Text Slider](./text-slider)** 🔁 | A looping word slider: *make **lifestyle / work / everything** awesome!* — each word slides in on its own colour band. | `@keyframes`, absolute positioning, `overflow: hidden`, seamless infinite loop |
| 3️⃣ | **[Solar System](./solar-system)** ☀️ | The Earth orbiting a glowing sun in 3D space over a night-sky background, with the planet texture spinning as it travels. | `preserve-3d`, `translate3d`, `rotateX`, `transform-origin`, `@keyframes`, `box-shadow` glow |

> 📌 More experiments will be added over time.

---

## 📂 Repository Structure

```text
css-animation-experiments/
│
├── README.md
├── .gitignore
│
├── hamburger-menu/
│   ├── index.html
│   └── assets/
│       ├── css/
│       │   ├── public.css        # Global reset
│       │   └── master.css        # Menu styles & animations
│       └── icons/
│           └── font/             # Custom icon font (style.css + fonts/)
│
├── text-slider/
│   ├── index.html
│   └── assets/
│       └── css/
│           ├── public.css
│           └── master.css
│
└── solar-system/
    ├── index.html
    └── assets/
        ├── css/
        │   ├── public.css
        │   └── master.css
        └── images/               # Night sky, sun and earth textures
```

Each project is fully self-contained: it has its own `index.html` and `assets/` folder, so you can copy any one of them out and it will keep working.

---

## 🚀 Getting Started

No tools required — it is plain HTML & CSS.

**1. Clone the repository**

```bash
git clone https://github.com/mohammadtakali/css-animation-experiments.git
cd css-animation-experiments
```

**2. Open a project**

Open the `index.html` inside any project folder, or serve the whole repo locally:

```bash
npx serve .
# or
python3 -m http.server
```

> 💡 **Tip:** The CSS uses native nesting, so use an up-to-date browser (Chrome 120+, Edge 120+, Safari 17.2+, Firefox 117+).

---

## 🌐 Live Demos

Every project runs live on **GitHub Pages**:

| Project | Live Demo |
|---------|-----------|
| 🍔 Hamburger Menu | [Open demo](https://mohammadtakali.github.io/css-animation-experiments/hamburger-menu/) |
| 🔁 Text Slider | [Open demo](https://mohammadtakali.github.io/css-animation-experiments/text-slider/) |
| ☀️ Solar System | [Open demo](https://mohammadtakali.github.io/css-animation-experiments/solar-system/) |

> 💡 Best viewed on desktop with an up-to-date browser.

---

## 👤 Author

**Mohammad Takali** — Front-end Developer

- 🐙 [GitHub](https://github.com/mohammadtakali)
- 💼 [LinkedIn](https://www.linkedin.com/in/mohammad-takali-b9b820434)
- 📸 [Instagram](https://instagram.com/mohammadtakali.dev)

---

<p align="center">Made with ❤️ and pure CSS</p>
