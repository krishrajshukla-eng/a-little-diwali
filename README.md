# A Little Diwali

**A small 3D Diwali greeting, made to share a little warmth.**

This is a personal, beginner-friendly web project by **Krishraj Shukla**. It turns a few lines of festive wishes into a little interactive night scene: a home, diyas, a family, and fireworks.

**Website:** [a-little-diwali](https://krishrajshukla-eng.github.io/a-little-diwali/) ·
**Source:** [GitHub repository](https://github.com/krishrajshukla-eng/a-little-diwali)

It is a simple creative project, not a realistic Diwali simulation. The scene uses stylised 3D shapes; the focus is on a warm greeting, not photorealism.

## What you can do

- Open it on a phone or computer; the layout adjusts to the screen.
- Drag the scene to look around, or tap it for another wish.
- Use **A wish for you** to cycle through the messages.
- Use **Share** to open your device's share options, or copy the link where supported.
- Enjoy occasional fireworks, with motion kept lighter for visitors who prefer reduced animation.

## Try it on your computer

1. Download or clone this project.
2. Open a terminal in the project folder.
3. Run `python3 -m http.server 8000`.
4. Visit `http://localhost:8000` in your browser.

The page loads Three.js from jsDelivr, so an internet connection is needed for the 3D scene. The rest of the page is a single HTML file; there is no build step, backend, or account system.

## Publish and share

The site is deployed from this dedicated public repository with GitHub Pages. Updates to `index.html` or the deployment workflow on `main` publish automatically. This repo contains only the website and its documentation; the original tutorial repository stays private.

## A note on the Share button

The Share button uses the browser's native share sheet when available. Otherwise, it tries to copy the current page URL; clipboard access depends on browser permissions and a secure hosted page. The button cannot turn a local file into a public website by itself.

---

Made with light and love by **Krishraj Shukla**.
