# Cube Dodge

A 3D browser-based dodge game built with Three.js where you control a blue cube avoiding colliding spheres while collecting points.

## Description

In Cube Dodge, you control a blue cube on a flat surface. Golden spheres spawn at the edges and move towards the center. Collect them for points, but be careful - when spheres collide, they create expanding shockwaves that can damage you. However, skilled players can risk getting close to shockwaves for bonus lives!

## Features

- 3D graphics using Three.js
- Smooth controls (WASD/Arrow keys)
- Dynamic difficulty scaling
- Collision detection and physics
- Shockwave system with risk/reward mechanics
- Adjustable parameters (spawn rate, ball speed)
- Pause functionality
- Score tracking
- Lives system with bonus life opportunities

## Controls

- **Movement**: WASD or Arrow keys
- **Pause**: P key
- **Spawn Rate Adjustment**: + / - buttons in top right
- **Ball Speed Adjustment**: + / - buttons in top right

## Gameplay Mechanics

- **Basic Movement**: Control the blue cube to collect golden spheres
- **Scoring**: Each collected sphere adds 1 point
- **Lives**: Start with 5 lives
- **Shockwaves**: Created when spheres collide
  - Getting hit by a shockwave costs 1 life
  - Getting close to a shockwave (in the red ring) without being hit awards 2 bonus lives
- **Difficulty**: Spawn rate gradually increases as you play

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
```

2. Open `index.html` in a modern web browser

## Requirements

- Modern web browser with WebGL support
- Three.js (included via CDN)

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Three.js (3D graphics library)

## License

[Add your chosen license here]