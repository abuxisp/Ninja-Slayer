# Ninja-Slayer

## Game Description
**Ninja-Slayer** is an action-adventure web game built with JavaScript[cite: 1] where players step into the shoes of a swift ninja navigating a richly layered world. Featuring custom pixel art assets, environmental decorations[cite: 1], and interactive elements like monsters, hearts, and lances, players must explore detailed landscapes, manage collisions[cite: 1], and survive encounters with various threats to master the way of the ninja.

---

## Project Structure
The repository is organized into the following key directories and files[cite: 1]:
*   **`classes/`**: Contains core object-oriented components for game entities:[cite: 1]
    *   `Player.js`: Handles player state, movement, and controls[cite: 1].
    *   `Monster.js`: Manages enemy entities and behaviors[cite: 1].
    *   `CollisionBlock.js`: Manages map boundaries and solid obstacles[cite: 1].
    *   `Heart.js`: Handles health pickups[cite: 1].
    *   `Sprite.js`: Base rendering class for visual elements[cite: 1].
*   **`data/`**: Holds map layouts, collision arrays, and environmental layer data (e.g., terrain, trees, houses, decorations, and front renders)[cite: 1].
*   **`images/`**: Houses all graphical assets including character sprites, tilesets, terrain, bamboo, hearts, lances, and dragons[cite: 1].
*   **`js/`**: Contains game logic execution scripts:[cite: 1]
    *   `index.js`: Main entry point and game loop[cite: 1].
    *   `eventListeners.js`: Manages keyboard and user inputs[cite: 1].
    *   `utils.js`: Helper functions used across the codebase[cite: 1].
*   **`index.html`**: The main webpage hosting the game canvas[cite: 1].

---

## How to Play

### Controls
*   **Movement:** Use the arrow keys or standard directional inputs (configured via `eventListeners.js`) to move your ninja character across the map[cite: 1].
*   **Interaction:** Navigate around obstacles, avoid enemy monsters, and collect items like hearts to maintain health[cite: 1].

### Objectives
1.  **Explore:** Traverse through the multi-layered environment consisting of terrain, trees, houses, and decorative elements[cite: 1].
2.  **Survive:** Avoid colliding with hostile monsters and hazards mapped into the game blocks[cite: 1].
3.  **Collect:** Gather power-ups and health items (such as hearts) hidden or placed throughout the levels[cite: 1].

---

## Want to play?
https://abuxisp.github.io/Ninja-Slayer/
