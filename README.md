# CatRunner Game

 # Game Mechanics Overview

- When the game starts, the player sees:
  - A character
  - Platforms (some with hidden spikes)
  - A fence
  - Multiple windows
  - Clouds
  - Coins of various values
  - A roaming enemy

- **Controls:**
  - Move the character using **W, A, S, D** or the **arrow keys**.
  - The player can jump onto and off platforms and fences.

- **Platforms:**
  - Spikes randomly appear on platforms.
  - If the player is standing on a platform when spikes appear, they fall down.

- **Enemies:**
  - An enemy randomly appears from time to time.
  - It moves along the lower level from left to right or right to left.
  - Contact with the enemy results in player death.

- **Player Lives and Respawn:**
  - If the player dies (by spikes or enemy), they return to the beginning of the level and lose one life.
  - The game ends when all lives are lost.

- **Level Progression:**
  - The player must:
    1. Jump onto a low platform
    2. Then to a higher platform
    3. Then onto the fence
    4. Finally, jump into a window to win the game

- **Window Hazards:**
  - When the player jumps on the fence, one of 12 windows randomly opens.
  - Spikes may shoot from the open window in a parabolic arc toward the player.

- **Cloud Interaction:**
  - The player can cling to clouds and move across them.
  - There are three layers of clouds, each holding a coin of different value.
  - Falling off a cloud sends the player back to the start.

- **Coins and Hazards:**
  - Coins can move randomly within their cloud layer.
  - Some coins may shoot straight-flying spikes at the player.
  - Collecting coins increases the player’s score.

- **HUD (Heads-Up Display):**
  - The top-left corner of the screen displays:
    - Number of lives remaining
    - Total points collected