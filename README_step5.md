# Step 5: Expanding Teams to Five Players Each and Enhancing Movement Logic

## Overview
Step 5 not only increases the number of players per team to five but also introduces enhanced movement logic to maintain a realistic spacing between players on the same team.

## Key Features
- **Increased Team Size**: Each team now consists of five players, adding more complexity to the simulation.
- **Enhanced Player Movement Logic**: Players maintain a minimum distance from their teammates, preventing clustering while actively participating in the game.

## Implementation Details
- Adjusted player creation to generate a total of ten players, five for each team.
- Implemented a `move-away` mechanism, where players avoid getting too close to their teammates.
- Balanced the movement logic to ensure players engage in offensive or defensive actions, depending on the game situation.

## Next Steps
- Further development of team strategies, including positioning and movement based on game dynamics.
- Introduction of advanced tactics for offensive and defensive play.
