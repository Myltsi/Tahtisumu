# Tähtisumu

Tähtisumu is a top-down space shooter made with Godot. Pilot your spacecraft,
destroy waves of enemies and survive for as long as possible while the
difficulty increases.

## Game concept

The player defends themselves against enemies approaching through space.
Enemies spawn around the edges of the play area and move towards the player.
A wave ends when all of its enemies have been destroyed, after which the next
wave begins with more enemies.

The game ends when the spacecraft runs out of lives. The goal is to survive as
many waves as possible.

## Key features

- Wave-based survival gameplay with increasing difficulty.
- A mouse-aimed spacecraft and projectile-based combat.
- Two enemy types:
  - a regular enemy that charges towards the player
  - a tougher enemy that requires multiple hits
- A dash that temporarily gives the spacecraft a significant speed boost and
  activates a shield. The shield allows the player to destroy enemies by
  colliding with them during the dash.
- Portals that allow the player to move quickly between locations in space.
- Items dropped by enemies:
  - **Health** adds one extra life
  - **Rapid Fire** temporarily increases the firing speed
- An in-game HUD showing lives, the current wave, the number of enemies in the
  wave and the dash cooldown.
- Pause, restart and main menu functionality.
- Pixel art graphics, animations, sound effects and background music.

## Controls

| Action | Key |
| --- | --- |
| Move forward towards the mouse | `W` + mouse |
| Move backward away from the mouse | `S` + mouse |
| Move left | `A` |
| Move right | `D` |
| Shoot | Left mouse button |
| Dash and shield | `Shift` |
| Pause | `Esc` |

The spacecraft rotates towards the mouse cursor. The dash has a cooldown and
cannot be used continuously.

## How to play

1. Select **New Game** from the main menu.
2. Move and aim with the mouse.
3. Shoot approaching enemies before they hit the spacecraft.
4. Use the dash both for evasion and for destroying enemies.
5. Collect items dropped by enemies.
6. Survive the waves and try to beat your high score.

## Running the game

### Windows release

If you are using the Windows release, launch the included executable, for
example `Tähtisumu.exe`.

### In the Godot editor

1. Install [Godot 4.3](https://godotengine.org/download/).
2. Open `project.godot` from this directory in the Godot editor.
3. Press **Play** to launch the project. The main menu opens automatically.

## Technology

- [Godot Engine](https://godotengine.org/)
- Godot 4.3
- GDScript
- 2D game using the Compatibility renderer

## License

This project is released under the MIT License. See [`LICENSE`](LICENSE) for
more information.
