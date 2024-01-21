# Step 1: Basic Player and Ball Setup with Passing Logic

## Overview
In this initial step of our NetLogo soccer simulation, we've established the foundational elements of the game:
- Players represented as agents in the simulation.
- A ball that players can pass to each other.

## Implementation Details
- **Players and Ball Creation**: We have defined two breeds of agents - players and a ball. Players are initialized with random positions in the simulation environment.
- **Random Player Movement**: Players move randomly around the environment.
- **Passing Logic**: When a player is near the ball, they pass it to another randomly chosen player.

## NetLogo Procedures
- `setup`: Initializes the environment, players, and ball.
- `move-players`: Defines random movement behavior for players.
- `pass-ball`: Implements the logic for players to pass the ball to each other.

The code at this stage serves as a foundation for further development and complexity that will be added in subsequent steps.
