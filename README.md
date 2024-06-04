# Game Mechanics

This project is a collection of standard game mechanics designed to be easily integrated into any game project. The mechanics include Health System, Respawn, Weapon, Inventory, and the most recent addition, Artificial Intelligence (AI). Each mechanic is implemented as an actor component, making it simple to clone and use in different projects.

## Features
- Actor Component-Based Design: Each mechanic is encapsulated in an actor component, allowing for easy integration and replication across different projects.
- Expandable Variants: Each mechanic is designed to support the creation of new variants without requiring edits to the existing logic.

## Available Mechanics
### Health System
- Manages player or NPC health.
- Supports damage, healing, and death events.
- Configurable health parameters (e.g., max health, damage).

### Respawn
- Handles the respawn logic for players.
- Configurable respawn points.

### Weapon
- Manages weapon functionalities, including firing, reloading, and ammunition.
- Supports multiple weapon types and switching.
- Configurable weapon parameters (e.g., damage, distance, shots per shell).

### Inventory
- Manages the player's inventory system.
- Supports adding, removing, and using items.
- Configurable inventory slots and item stacking.

### Artificial Intelligence (AI)
- Implements AI behaviors for NPCs.
- Supports state machines, pathfinding, and decision-making processes.
- Configurable AI parameters (e.g., aggression level, patrol routes).

## Project Structure
- Components: Contains all actor components, each representing a different game mechanic.
- Examples: Provides example usage for each mechanic.

## Running the Game

### Launch the game: 

- The game is currently under development and not yet available for public release. We are actively working on it and will provide updates as progress is made. Stay tuned for more information!

### Requirements
- Unreal Engine 5.4 installed

### Installation
1. Clone the repository:

   ```bash
   git clone https://github.com/AlexWalkerGD/Mechanics_Unreal.git

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes.
- Commit your changes (git commit -am 'Add new feature').
- Push to the branch (git push origin feature-branch).
- Create a new Pull Request.
