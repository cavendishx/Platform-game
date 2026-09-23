# 🐰 Bunny Fury

**Bunny Fury** is a platform game developed in **C++** using the **ncurses** library in 2023.

The player controls a bunny hero who explores different levels, defeats enemies, collects items, and earns **points and money**. The difficulty progressively increases, and the money can be used in the **Market** to purchase useful items.

## 🎮 Gameplay

* Movement across platforms and different levels
* Jumping and downward attacks
* Ranged attacks using projectiles
* Different types of enemies
* Item collection
* Score, lives, and money system
* Market for purchasing items
* Progressive difficulty
* Persistence of the state of previously explored levels

## ⌨️ Controls

| Key                   | Action                                           |
| --------------------- | ------------------------------------------------ |
| `←` / `→`             | Movement                                         |
| `←` / `→` (held down) | Continuous movement and temporary speed increase |
| `SPACE`               | Shoot a projectile                               |
| `↑`                   | Jump                                             |
| `↓` while jumping     | Downward attack                                  |

During a jump, the player can continue shooting and change the movement direction.

## 📋 Requirements

The following are required to compile the project:

* C++ compiler (g++)
* GNU Make
* ncurses library

On Windows systems, an environment that provides g++, make, and ncurses, such as MSYS2/MinGW, is required.

## 🚀 Getting Started

After cloning the repository, compile the project using:

```bash
make
```

This will generate the `BunnyFury.exe` executable.
