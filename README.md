# Ninja-Slayer
<img width="1282" height="717" alt="Screenshot 2026-11-02 002254" src="https://github.com/user-attachments/assets/3bc9c6a7-c344-4d13-a9e0-74b3dd97383f" />

# What the Game Is
Ninja-Slayer is a 2D browser-based action-adventure game built with HTML, CSS, and modular JavaScript. In this game, you step into the shoes of a swift ninja navigating a richly layered, custom pixel-art world filled with terrain, houses, trees, and environmental decorations.

# Why It Was Made
This project was built to explore core game development concepts using vanilla web technologies. It serves as a practical implementation of object-oriented programming in JavaScript, custom canvas rendering, multi-layered map building, and collision detection systems without relying on heavy external game engines.

# How It Works
The game relies on a structured architecture that separates logic, entities, map data, and visual assets:

Core Engine & Game Loop (js/): The main execution happens in index.js, which drives the canvas rendering loop. User inputs are captured via eventListeners.js, and helper utilities are handled in utils.js.

Object-Oriented Entities (classes/):

Player.js manages player states, movement controls, and interactions.

Monster.js handles enemy entities and behaviors.

CollisionBlock.js enforces map boundaries and solid obstacles.

Heart.js handles health and pickup mechanics.

Sprite.js acts as the base class for rendering visual graphics.

Map Data & Layering (data/): The world is constructed using array-based map layouts that separate background terrain, houses, landscape decorations, trees, collision maps, and foreground rendering layers.

Asset Pipeline (images/): Custom graphical assets—including character sprites, tilesets, bamboo, hearts, lances, leaves, and dragons—are dynamically loaded and drawn onto the HTML5 canvas.

# How to Play
Controls
Movement: Use your keyboard directional keys (arrow keys or standard inputs configured in eventListeners.js) to move your ninja across the map.

Survival: Navigate carefully around obstacles, avoid hostile enemy monsters, and collect items like hearts to manage your health.

Objectives
Explore: Traverse through the detailed multi-layered environment.

Survive: Evade enemy threats and respect the solid collision boundaries of the map.

Collect: Gather items and power-ups hidden throughout the game world.
---

## Want to play?
https://abuxisp.github.io/Ninja-Slayer/
