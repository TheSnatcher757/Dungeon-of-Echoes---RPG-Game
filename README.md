# Dungeon of Echoes

A roguelike dungeon crawler with procedurally generated levels, turn-based combat, fog of war, and RPG progression. Built with vanilla JavaScript and HTML5 Canvas.

**[Play Now](https://thesnatcher757.github.io/Dungeon-of-Echoes](https://thesnatcher757.github.io/Dungeon-of-Echoes---RPG-Game/)**

## Features

- Procedurally generated dungeons with rooms and corridors
- Turn-based movement and combat
- Fog of war with line-of-sight visibility
- 4 enemy types: Rat, Goblin, Skeleton, Demon
- Items: Health Potions, Strength Scrolls, Armor Shards, Gold
- Hidden traps on deeper floors
- XP and leveling system with stat progression
- Enemy HP bars and floating damage numbers
- Particle effects for combat and pickups
- Multiple dungeon floors with increasing difficulty

## Controls

- WASD or Arrow Keys to move
- Bump into enemies to attack
- Walk over items to pick them up
- Reach the stairs (>) to descend to the next floor

## How It Works

Each floor is procedurally generated using a room placement algorithm with corridor connections. Enemies scale with floor depth. The fog of war uses raycasting from the player position to determine visible tiles. Combat is turn-based with ATK vs DEF damage calculation.

## Tech

- Zero dependencies
- Pure JavaScript and HTML5 Canvas
- Procedural dungeon generation
- Line-of-sight fog of war
- Single file, no build step

## Author

**Angel Nunez**
B.S. Computer Science, San Diego State University
