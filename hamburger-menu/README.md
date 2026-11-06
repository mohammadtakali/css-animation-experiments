# 🍔 Hamburger Menu

A quarter-circle hamburger button pinned to the top-left corner. Hover over it and the whole page tilts away like a door while the menu items slide in one after another.

## 🔗 Live Demo

👉 [https://mohammadtakali.github.io/css-animation-experiments/hamburger-menu/](https://mohammadtakali.github.io/css-animation-experiments/hamburger-menu/)

## ✨ How it works

- 🔴 A fixed `150px` circle is pushed half off-screen (`top/left: -75px`) so only a quarter shows.
- 🔄 On `:hover` it rotates from `270deg` to `180deg`.
- 📄 The sibling selector `~` tilts the article (`rotate(-30deg)` with `transform-origin: 0 0`) at the same moment, revealing the dark panel underneath.
- 📜 Menu items slide in from the left with staggered `transition-delay` values (`0s`, `.4s`, `.8s`).
- 🔣 Icons come from a custom icon font loaded with `@font-face`.

## 🛠️ Stack

HTML5 · CSS3 · Custom icon font

## 🚀 Run

Open `index.html` in a browser.
