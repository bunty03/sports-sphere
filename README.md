## SPORTS SPHERE ( AN IDRP STARTUP )
"Sports Sphere is a platform that connects players across locations through an interactive website. It enables users to find and join games in turfs, private clubs, and grounds, fostering real-world sports connections. Along with offline matches, it also offers engaging online games, building a unified sports community."

## Sphere Packing 2

A WebGL / three.js-based visual project created on CodePen.  
Original live version: [Sphere Packing 2 on CodePen](https://codepen.io/soju22/pen/BaXgmpO) :contentReference[oaicite:0]{index=0}

---

## Project Description

*Sphere Packing 2* is a dynamic visual / background animation featuring multiple spheres “packed” in 3D space. The spheres float, change colors, and interact via user input (clicks). It uses a WebGL canvas and an external sphere-background library to render an immersive sphere field.

Key interactions:

- **Pause / resume animation** by clicking on non-button areas of the screen  
- **Randomize colors** of spheres by clicking the “Random colors” button  
- Background is responsive and covers entire viewport via a `<canvas>`  

The visual is implemented using a library: `Spheres2Background` (from `threejs-components`) to manage the sphere system. :contentReference[oaicite:1]{index=1}

---

## Technology Stack

- **HTML / CSS / JavaScript** (ES Modules)  
- **three.js / WebGL** (via `Spheres2Background` external module)  
- **CDN import** for the sphere background component  

---

## Project Structure

- `index.html` — HTML markup including the canvas and UI (button).  
- `styles.css` — CSS for layout, backgrounds, typography.  
- `script.js` — JavaScript logic: importing `Spheres2Background`, initializing, handling interactions.  
- `assets/` — optional directory for fonts, images etc.  
- `README.md` — this documentation file.  

---

## Setup & Usage

1. **Clone / download** this repository  
2. **Open** `index.html` in a modern browser (supporting ES modules)  
3. (Optional) Use a local development server for better module support, e.g.:

```bash
npx http-server .   # or python3 -m http.server 






