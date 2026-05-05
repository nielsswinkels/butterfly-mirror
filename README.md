# Fjärilsskogen — AR Butterfly Mirror

An augmented reality experience where participants stand in front of a camera and see themselves transformed with butterfly wings against an enchanted forest background. Originally built for a kids' birthday party.

## Features

- **Real-time person segmentation** — detects people via webcam and overlays animated butterfly wings
- **Multi-person tracking** — supports multiple participants simultaneously
- **Coloring scan mode** — print a butterfly template, color it in with real crayons, then scan it with the camera to release your own design as a butterfly flying in the forest
- **Animated forest background** — procedurally generated trees with moss and roots
- **Rainbow gesture** — raise both hands above your shoulders for a rainbow effect
- **Keyboard shortcuts** — control the scan flow from a keyboard

## How to Use

1. Open `index.html` in a browser (requires webcam access)
2. Stand in front of the camera — wings appear automatically
3. Press the **Scan** button to enter scan mode:
   - Print `template.html` as a coloring page
   - Color in the butterfly wings
   - Hold the colored page up to the camera within the guide rectangle
   - Confirm to apply your design as wing texture

## Tech

Single-page HTML/JS app using:
- [MediaPipe](https://developers.google.com/mediapipe) for person segmentation and pose detection
- Canvas 2D for rendering

No build step required — just serve the files or open directly in a browser.
