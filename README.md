# Solar System with Spaceship – Three.js

This project is a simple solar system simulation built using **Three.js**. It features planets, moons, and a spaceship you can pilot through the scene.

## Controls

### Camera
- **Left Mouse Button (LMB)**: Rotate around the solar system (implemented via `OrbitControls`).
- **Scroll Wheel**: Zoom in/out.
- **Right Mouse Button / Drag**: Pan (if enabled in OrbitControls).

### Spaceship
- **Movement**
  - `W` – Move forward
  - `S` – Move backward
  - `A` – Strafe left
  - `D` – Strafe right
- **Rotation**
  - `Arrow Up` – Pitch up (rotate upwards)
  - `Arrow Down` – Pitch down (rotate downwards)
  - `Arrow Left` – Yaw left (rotate left)
  - `Arrow Right` – Yaw right (rotate right)
- **Toggle camera view**
  - `C` – Switch between orbital camera and spaceship cockpit view

## Features
- Realistic orbital motion of planets and moons
- Day/Night textures for Earth
- Background galaxy (Milky Way) mapped onto a sky sphere
- Basic lighting and shadows
- Spaceship model with cockpit camera

## Contributions / Assets

### Spaceship
- Model: [Low-Poly Spaceship](https://free3d.com/3d-model/low-poly-spaceship-37605.html)

### Textures
- Planet textures: [NASA 3D Resources](https://github.com/nasa/NASA-3D-Resources/tree/master/Images%20and%20Textures)
- Additional textures: [Humboldt 3D Textures Archive](https://gis.humboldt.edu/Archive/GISData/2019/WGS84_Geographic/3DTextures)

## Usage
1. Clone the repository.
2. Install dependencies (Three.js, OrbitControls, OBJLoader, MTLLoader).
3. Open `index.html` in a modern browser (or serve via local HTTP server for CORS).
4. Fly around the solar system using the spaceship controls or orbit with the camera.

