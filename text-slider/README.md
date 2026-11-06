# 🔁 Text Slider

A looping word slider that reads *"make **lifestyle / work / everything** awesome!"* — each word slides up on its own colour band.

## 🔗 Live Demo

👉 [https://mohammadtakali.github.io/css-animation-experiments/text-slider/](https://mohammadtakali.github.io/css-animation-experiments/text-slider/)

## ✨ How it works

- 🪟 The middle line is a `50px`-tall window (`overflow: hidden`).
- 📚 Inside it, a `ul` of stacked `li` items is absolutely positioned and animated with `@keyframes` by changing its `top` value (`0 → -50px → -100px → -150px`).
- ⏸️ Each word pauses for a moment, then slides to the next one.
- ♾️ The last item repeats the first one (same word, same colour), so the jump back to the start is invisible and the loop looks endless.

## 🛠️ Stack

HTML5 · CSS3

## 🚀 Run

Open `index.html` in a browser.
