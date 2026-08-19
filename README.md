# Space Invaders Clone

A simple Space Invaders-style arcade game written in C for the Windows console.

The game features real-time keyboard controls, moving aliens, player and enemy bullets, scoring, lives, collision detection, and win/game-over conditions.

## 👥 Contributors & Module Breakdown

This project was built collaboratively by a team of 4 members, each designing and implementing specific mathematical modules:

| Contributor | Assigned Modules & Features |
| :--- | :--- |
| **Saiful** | Structures (Aliens and Bullets) |
| **I** | gamestate |
| **me** | graphics |
| **myself** | Debugging |

---

## 🎮 Features

- Real-time keyboard controls — no Enter key required

- Move the spaceship left and right

- Shoot multiple bullets

- Aliens move horizontally and descend when reaching the edge

- Random enemy shooting

- Bullet collision detection

- Score system

- 3-player-lives system

- Win condition when all aliens are destroyed

- Game-over condition when all lives are lost or aliens reach the player

- Console cursor hiding for a cleaner game experience

- Simple ASCII-based graphics

## 🎮 Controls

```
A                            Move Left
D                            Move Right
Space                        Shoot
Q                            Quit
```

No Enter key is required for gameplay. The game starts as soon as the code is run on Code::Blocks.

🖥️ Requirements

This project is designed for Windows because it uses:

- conio.h
- windows.h
- MinGW/GCC

You will need:

- Windows
- GCC / MinGW
- A Windows terminal or console

## ⚙️ Compilation

Save the source code as:

`space_invaders.c`

Compile it with MinGW:

`gcc space_invaders.c -o space_invaders`

Then run:

`space_invaders`

Or on Windows:

`space_invaders.exe`

## 🎯 Gameplay

You control the spaceship at the bottom of the screen:
```
############################################################
#                                                          #
#       W      W      W      W      W      W      W        #
#                                                          #
#       W      W      W      W      W      W      W        #
#                                                          #
#                         |                                #
#                                                          #
#                       < ^ >                              #
############################################################
```
Destroy the aliens before they reach your spaceship.

Each alien destroyed gives you:

+10 points

You start with:

Lives: `3`
