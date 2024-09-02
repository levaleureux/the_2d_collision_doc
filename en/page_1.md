# Basic 2D Collision Categories

This document outlines the basic categories of 2D collisions for a platformer game without moving platforms, 
enemies, or collectables, but including wall climbing and wall bouncing mechanics.

## 1. Collision with the Ground
- **Ground Detection**: The player's sprite detects when it touches the ground, preventing it from falling through.
- **Ground Bounce**: When the player lands on the ground, they stop descending and can walk or jump again.

## 2. Collision with Walls
- **Horizontal Collision**: The player's sprite stops when it comes into contact with a wall on the left or right side.
- **Wall Sliding**: The player can slide along a wall when in the air and in contact with the wall.
- **Wall Bounce**: The player can perform a "wall jump," bouncing off a wall to reach higher areas or change direction mid-air.
- **Wall Climbing**: The player can climb or grip certain types of walls to ascend higher.

## 3. Collision with Ceilings
- **Ceiling Detection**: Prevents the player from passing through a ceiling when jumping.
- **Bounce Downward**: If the player hits a ceiling, they are pushed downward.

## 4. Collision with Destructible Blocks
- **Block Destruction**: The player can break certain blocks when jumping up into them or hitting them with sufficient force.

## 5. Collision with Screen Boundaries
- **Level Boundaries**: The player cannot move outside the defined play area (left/right edges or ceiling/floor).
- **Instant Death**: If the player falls off the screen (beyond the floor), they die.

## 6. Collision with Semi-Solid Platforms
- **Pass Through from Below**: The player can jump through a platform from below but lands on it when descending.

These categories should cover the essential collision interactions in a 2D platformer game without enemies or collectables, 
but with wall climbing and wall bouncing mechanics.
