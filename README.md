# Lunar-Lander-AI

## ITCS 4236/5236 Group Project

### Group Members:
- **Surabhi Parab** - [sparab2@charlotte.edu](mailto:sparab2@charlotte.edu)
- **Alka Wilson** - [awils214@charlotte.edu](mailto:awils214@charlotte.edu)

---

## Overview

**Lunar Lander Using AI** is a 2D simulation game where players control a lunar lander, attempting to safely land on various celestial bodies. The game introduces AI to simulate real-life challenges like gravity, fuel management, and uneven terrain, either aiding or challenging the player. The AI component uses pathfinding algorithms to calculate optimal landing strategies.

## Gameplay Mechanics

### Major Mechanics:
- **Landing Control**: Players control the lander’s thrust and orientation to guide it to a safe landing zone.
- **Fuel Management**: Players must manage their fuel efficiently to ensure a safe landing.
- **Terrain Variance**: The game features a variety of terrain types, from flat surfaces to steep slopes and obstacles.
- **Dynamic Environment Simulation**: The simulation includes changing environments, such as shifting terrain, variable gravity, and anomalies that affect gameplay.

### Minor Mechanics:
- **Scoring System**: Players earn points based on landing accuracy, fuel efficiency, and time taken to land.
- **Difficulty Levels**: Multiple levels of difficulty are available, each adding more challenges like increased gravity, reduced fuel, or more difficult terrain.

## AI Component

The AI uses the **A\* (A-star) algorithm** to:
- Find the safest and most fuel-efficient landing path.
- Adapt to the player’s skill level by introducing new challenges dynamically, like variable gravity, gusts of wind, or uneven terrain.
- Predict issues such as fuel shortages or harsh landing conditions and provide real-time advice.
- Continuously calculate the best trajectory based on changing environmental variables and player input.

---

## How to Play
1. **Control**: Use keyboard inputs to control the lander's thrust and orientation.
2. **Objective**: Safely land the lunar lander while managing fuel and avoiding obstacles.
3. **AI Help**: The AI provides landing path suggestions, but players can choose to ignore or follow them.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Alkawil/Lunar-Lander-AI.git
