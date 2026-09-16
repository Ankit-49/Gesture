# Hand Gesture Particle System

A gesture-controlled 3D particle playground built with **Three.js** and **MediaPipe Hands**.

## Gestures

- **Open Palm**: Expands particles and eases back.
- **Pinch**: Cycles color schemes.
- **Three Fingers**: Switches to the next particle template.
- **Peace Sign**: Switches to the previous particle template.
- **Thumbs Up**: Resets to default state.

## Keyboard Controls (Fallback)

- **Right Arrow**: Next particle template.
- **Left Arrow**: Previous particle template.
- **C**: Cycle color schemes.
- **R**: Reset to default state.
- **Space**: Expand particles and ease back.

## Reliability Notes

- Gesture recognition uses short-term stabilization to reduce flicker before actions trigger.
- If camera or hand-tracking setup fails, the app shows a status message instead of crashing.

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

## Troubleshooting

- If you see **Hand tracking unavailable**, verify network access to CDN scripts and reload.
- If you see **Camera access failed**, allow browser camera permissions and try again.
