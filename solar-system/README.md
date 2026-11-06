# ☀️ Solar System

The Earth orbiting a glowing sun in 3D space, set against a starry night sky — all with pure CSS.

## 🔗 Live Demo

👉 [https://mohammadtakali.github.io/css-animation-experiments/solar-system/](https://mohammadtakali.github.io/css-animation-experiments/solar-system/)

## ✨ How it works

- 🌌 The `section` uses a night-sky image as its background and `transform-style: preserve-3d` to create a 3D scene.
- ☀️ The sun is a circular div with a sun texture and a large golden `box-shadow` glow, pushed forward on the Z axis.
- 🪐 The orbit is a circle tilted with `rotateX(87deg)`, so the Earth travels in an almost edge-on ellipse.
- 🌍 The Earth rotates around the orbit using `transform-origin` set to the orbit radius, driven by an 80-second linear `@keyframes` loop.
- 🔄 Inside it, a second element with a world-map texture rotates and scrolls its `background-position`, giving the illusion of a spinning planet.

## 🛠️ Stack

HTML5 · CSS3

## 🚀 Run

Open `index.html` in a browser.
