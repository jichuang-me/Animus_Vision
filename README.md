# Chromatic Animus 🌈🐾

A fluid, hand-gesture controlled particle sensory experience built with Three.js and MediaPipe.

## Features

- **Fluid Physics**: High-performance particle system with 35,000 particles.
- **Hand Gesture Control**: Use your camera and hand gestures to transform particles into different animal shapes.
- **Multi-Modal Input**: Supports camera gestures, mouse double-clicks, and horizontal drag scrubbing to control morphing.
- **Visual Evolution**: From a chaotic void to detailed animal models (Rabbit, Bird, Cat, Dog, Tree, Star).

## How to use

1. Open `index.html` in a modern browser.
2. Click **"INITIATE NEURAL VISION"** to allow camera access for gesture control.
3. Use finger counts to change shapes:
   - 1 finger: Decorated Tree 🎄
   - 2 fingers: Soft Rabbit 🐰
   - 3 fingers: Phoenix Bird 🐦
   - 4 fingers: Calico Cat 🐱
   - 5 fingers: Golden Dog 🐶
   - Fist (0 fingers): Prism Star ✨
4. **Scrub Morphing**: Click and drag your mouse horizontally to manually scrub through the transformation process.
5. **Double Click/Tap**: Cycle through shapes manually.

## Technology Stack

- [Three.js](https://threejs.org/) for 3D rendering.
- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html) for ML-based hand tracking.
- Vanilla JavaScript & CSS.
