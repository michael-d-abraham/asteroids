# Asteroids

A small **Asteroids-style game** built with Python and [Pygame](https://www.pygame.org/). You pilot a ship in space, steer and thrust, shoot asteroids (rocks), and dodge collisions.

## Requirements

- Python 3
- `pygame`

Install Pygame:

```bash
pip install pygame
```

## How to run

From this folder:

```bash
python main.py
```

The window opens at **1400×700** pixels, running at **30 FPS**.

## Controls

| Action | Keys |
|--------|------|
| Turn left | **A** or **←** |
| Turn right | **D** or **→** |
| Thrust | **W** or **↑** |
| Shoot | **Space** |
| Quit | **Escape** or close the window |

## Project layout

- **`main.py`** — Entry point; wires keyboard input to the game loop.
- **`game.py`** — Window, timing, and event loop.
- **`asteroids.py`** — Main game logic (ship, rocks, bullets, stars).
- **`ship.py`**, **`rock.py`**, **`bullet.py`**, **`star.py`** — Game objects.
- **`polygon.py`**, **`circle.py`**, **`movable.py`**, **`rotatable.py`** — Drawing and movement helpers.
