# 3D Interactive Cube Viewer

A web-based 3D cube viewer built with Three.js, featuring interactive controls and animations.

## Project Overview

This project demonstrates a 3D cube with the following features:
- Interactive rotation using mouse drag
- Zoom control with mouse wheel
- Automatic rotation animation (can be toggled)
- Reset view functionality
- Responsive design

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6 modules)
- **3D Library**: Three.js v0.160.0
- **Backend**: Node.js + Express
- **Platform**: Windows

## Project Structure

```
3d-cube-viewer/
├── server.js              # Express server
├── package.json           # Dependencies
├── public/
│   ├── index.html        # Main HTML page
│   ├── style.css         # Styling
│   └── app.js            # Three.js application logic
└── README.md
```

## Installation

1. Install dependencies:
```bash
npm install
```

2. Start the server:
```bash
npm start
```

3. Open browser and navigate to:
```
http://localhost:3000
```

## Features

### Interactive Controls
- **Drag**: Click and drag to rotate the cube
- **Scroll**: Use mouse wheel to zoom in/out
- **Reset Button**: Reset camera to initial position
- **Animation Toggle**: Start/stop automatic rotation

### Visual Elements
- Gradient background
- Phong material with lighting
- Wireframe overlay
- Smooth camera controls with damping

## Known Issues

The application currently has several bugs that need to be fixed:
1. Material rendering issues with transparency
2. Mouse control direction problems
3. Animation timing inconsistencies
4. Incomplete reset functionality

## Requirements

- Node.js 14.x or higher
- Modern web browser with WebGL support
- Windows operating system

## License

MIT
