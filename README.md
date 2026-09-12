# Hand Gesture Particle System

A gesture-controlled 3D particle playground built with **Three.js** and **MediaPipe Hands**.

## Gestures

- **Open Palm**: Expands particles and eases back.
- **Pinch**: Cycles color schemes.
- **Three Fingers**: Switches to the next particle template.
- **Peace Sign**: Switches to the previous particle template.
- **Thumbs Up**: Resets to default state.

## Available Particle Templates

The app cycles through:

- Galaxy
- Heart
- Flower
- Saturn
- Fireworks
- Spiral
- Cube
- Sphere
- Torus
- DNA
- Wave
- Tornado
- Constellation
- Atomic
- Phoenix

## Run Locally

1. Open this repository folder.
2. Serve files with a local static server (for example: `python -m http.server 8000`).
3. Visit `http://127.0.0.1:8000/gesture.html` in a browser.
4. Allow camera access when prompted.
