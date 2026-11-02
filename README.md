# A Little Diwali

**A small 3D Diwali greeting, made to share a little warmth.**

This is a personal, beginner-friendly web project by **Krishraj Shukla**. It opens with a diya lighting and curtains parting onto a family celebration: a decorated two-storey home, flowering trees, a Lakshmi-Ganesh wall photo, an illustrated Ram Darbar beside an overflowing gold pot, and children enjoying sparklers and a rocket.

It is a simple creative project, not a realistic Diwali simulation. The scene uses stylised 3D shapes; the focus is on a warm greeting, not photorealism.

## What you can do

- Open it on a phone or computer; the layout adjusts to the screen.
- Light the diya to open the curtains and reveal the 3D scene.
- Drag the scene to look around; use the zoom buttons, mouse wheel, or a two-finger pinch to zoom.
- Tap the scene for another wish.
- Use **A wish for you** to cycle through the messages.
- Use **Share** to open your device's share options, or copy the link where supported.
- Enjoy falling gold coins, occasional fireworks, and a rocket launch; motion is kept lighter for visitors who prefer reduced animation.

## Try it on your computer

1. Download or clone this project.
2. Open a terminal in the project folder.
3. Run `python3 -m http.server 8000`.
4. Visit `http://localhost:8000` in your browser.

The page loads Three.js from jsDelivr, so an internet connection is needed for the 3D scene. The site uses one HTML page and the wall photo in `assets/`; there is no build step, backend, or account system.

## Publish and share

A link that works for other people needs a public host; a `localhost` link only works on your own computer.

This repository includes a GitHub Pages workflow in `.github/workflows/deploy-pages.yml`. A public site can be hosted from a public repository on GitHub Free; hosting from a private repository depends on your GitHub plan.

1. In GitHub, open the repository's **Settings → Pages** and enable Pages. The workflow cannot enable Pages automatically for this repository.
2. Set the build and deployment source to **GitHub Actions**.
3. Push `index.html` and the workflow to the repository's `main` branch.
4. After the **Deploy Diwali site** workflow succeeds, share the Pages URL GitHub shows.

Be aware: making an existing private repository public also makes its files and commit history public. Use a separate public repository if you do not want to expose unrelated work. Until Pages is enabled and deployment succeeds, there is no live public link to share.

## A note on the Share button

The Share button uses the browser's native share sheet when available. Otherwise, it tries to copy the current page URL; clipboard access depends on browser permissions and a secure hosted page. The button cannot turn a local file into a public website by itself.

---

Made with light and love by **Krishraj Shukla**.
