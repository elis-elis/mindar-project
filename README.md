# MindAR Test (Image Tracking AR with A-Frame)

This project is a basic augmented reality demo using [MindAR.js](https://hiukim.github.io/mind-ar-js-doc/) and [A-Frame](https://aframe.io/). It tracks an image and overlays 3D content using your webcam.

## 🚀 Features

- Image target recognition using `targets.mind`
- Simple AR content: plane and box overlay
- Camera auto starts when the image is detected

## 📁 Project Structure


## 🧰 Requirements

- Modern browser (Chrome recommended)
- Local HTTP server (e.g. Python, VS Code Live Server)

## ▶️ Running Locally

```bash

1. Start a local server:

# Python 3
python3 -m http.server 8000

2. Open in browser:

http://localhost:8000

3. Allow camera access and point it at your printed target image.


--------------------------------------------
Optional Add-ons
Replace <a-box> with a <a-gltf-model> to use 3D models

Add animation or interaction with A-Frame components

Notes
Make sure targets.mind and your target image match.

Best results with good lighting and printed (not screen) image.
