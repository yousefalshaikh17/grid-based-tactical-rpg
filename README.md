# Grid-based Tactical RPG (WIP)

### Overview

This passion project is inspired by the Fire Emblem franchise by Nintendo, and it is currently in its early stages of development. The goal is to create a tactical RPG with a deep combat system, similar to Fire Emblem, while expanding on core features such as battle animations and dynamic camera effects that zoom into battles.

A key aspect of this project is its grid-based movement system, which utilizes **Depth-First Search (DFS)** and **Dijkstra’s Algorithm** for pathfinding and movement cost calculations. These algorithms ensure that unit movement is both efficient and strategic, allowing for dynamic navigation across the battlefield while factoring in terrain and movement constraints.

The project is aimed at building a solid foundation for a tactical game with a focus on movement, combat mechanics, and interactive map design.

### Development & Features

The project is being developed on Roblox using their Luau programming language, with several key milestones already implemented:

- **Movement System**:
    - Developed a system where the player can move units across a grid-based map, with highlighted tiles indicating available movement zones (blue) and attackable tiles (red).
    - Implemented Depth-First Search (DFS) and Dijkstra’s Algorithm to efficiently calculate movement paths and attackable tiles based on unit movement costs.
- **Combat Mechanics**: Implemented basic combat mechanics for both melee and ranged attacks:
    - Melee and ranged attacks are fed a range value, allowing for a dynamic combat experience with varying attack ranges.
- **Tile Labeling System**: Created a system that labels tiles on the map, allowing map designers to streamline map creation and enhance design flexibility.
- **Camera and Battle Animations**: Plans for adding dynamic battle animations and a zooming camera effect during combat to create a more immersive experience.

### Real-World Applications

This project allowed me to explore game development for tactical RPGs and refine my understanding of combat systems, grid-based movement, and how interactive maps can be designed. The project also demonstrated my ability to implement systems for managing map design and combat mechanics. Moving forward, I hope to collaborate with map designers to build more complex environments and expand the gameplay.

### Videos showing off the project

Movement - Highlights tiles players can move to in blue. Red is attackable tiles.

https://github.com/user-attachments/assets/d6368de4-5e35-4068-8c78-bd8ba0b14e77

Melee Attacks - Very simple melee attack. (Min 1 Max 1 range)

https://github.com/user-attachments/assets/39629075-10a9-404e-bd82-b1fd17596066


Ranged Attacks - Ranged attack (Min 2 Max 2 range)

https://github.com/user-attachments/assets/630b2706-b07c-4fa7-99eb-8e4cc40ebcf9

### Future Plans
While still in the early stages, there is a lot planned for this game. I hope to expand upon the battle system, add more advanced battle animations, and further develop the game’s camera system. Collaboration with map designers is a key goal to further build the game's world, and I will continue to update this page as progress continues.

### Challenges & Learnings
Previous challenges included how to best implement algorithms to display the walkable and attackable terrains. This was used by using the Depth-First Search (DFS) algorithm. Current challenges involve how to execute proper battle animations and how to handle camera zooming into the scenery when a battle is initiated.
