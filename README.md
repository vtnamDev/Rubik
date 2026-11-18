# Rubik 3D Studio

Mobile-first 3D Rubik 3×3 playground built with Vite and Three.js.

## Interaction
- Face mode: tap a sticker to turn that face clockwise; swipe on it to choose the direction.
- Orbit mode: use the control above the 3D stage to switch to Orbit. Drag over the cube to rotate the camera; pinch or scroll to zoom.
- Use the crosshair control to restore camera framing for the current viewport.
- U, D, L, R, F, B controls, keyboard shortcuts, scramble, undo/redo, local records, Kociemba solver and the beginner guide are included.

## Local development
```bash
npm install
npm run dev
npm test
npm run build
```

The deployment build unpacks `rubik-3d.zip`, installs the pinned dependencies and publishes `dist/`.
