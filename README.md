# Side Quest Week 6

## Setup and Interaction Instructions

To run the sketch locally, open `index.html` in Google Chrome using Live Server.

**Controls:**

- Move: WASD
- Shoot: Spacebar (shoots in the direction you last moved)
- B: Skip to boss fight (testing only)
- Restart: R (after win or game over)

Explore the world, survive enemy waves as you move north, then enter the glowing boss zone to fight the giant orange blob. Watch the minimap to track enemies off screen.

**Adding Your Own Sounds**

1. Add your sound files to `assets/sounds/`
2. In `preload()`, uncomment the `loadSound()` lines and update the file paths
3. Uncomment the `play()` or `loop()` calls in the relevant functions — there are hooks for the boss music transition too

**Editing the Waves and Boss**
Open `data/enemies.json` to change when waves spawn, how many enemies appear, their speed, and the boss stats. Each wave has a `spawnAt` world Y value — lower values trigger later since the player starts at the bottom of the world.

**Opening the Chrome Console**

- **Windows:** Press `F12` or `Ctrl + Shift + J`, then click the **Console** tab
- **Mac:** Press `Cmd + Option + J`

## Assets

| File                           | Source                                                  |
| ------------------------------ | ------------------------------------------------------- |
| `assets/images/background.png` | [1]BlackDevilx, Midnight Village Pixel Art, AlphaCoders |
| `assets/images/Player.png`     | [2]princesa Kyra, Pintrest Image — Pintrest             |
| `assets/sounds/music.wav`      | Adobe Firefly.                                          |
| `assets/sounds/player_hit.wav` | Adobe Firefly.                                          |
| `assets/sounds/shoot.wav`      | Adobe Firefly.                                          |

## References

[1] BlackDevilx. n.d. Midnight Village Pixel Art HD Wallpaper. Alpha Coders Wallpaper Abyss. Retrieved June 17, 2026 from https://wall.alphacoders.com/big.php?i=1027689

[2] princesa Kyra. n.d. Pinterest image pin. Pinterest. Retrieved June 17, 2026 from https://ca.pinterest.com/pin/10203536652010401/
