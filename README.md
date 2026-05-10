# MODUS — 2D Dungeon Crawler

 A C++ game built from the 
ground up with SFML, featuring 4 levels, a custom physics and 
animation system, and MySQL-backed save persistence.

## Architecture
Source lives in `final task1/`:
- `main.cpp` — game loop and state management
- `Hero.cpp` / `enemy.cpp` — entity classes with attack/movement logic
- `collision.cpp` — custom AABB collision detection (no engine)
- `Animation.cpp` / `AnimationNew.cpp` — sprite animation system 
  (refactored mid-development for performance)
- `obstacle.cpp`, `prize.cpp`, `material.cpp` — game object hierarchy

## Tech
- **Language:** C++
- **Framework:** SFML
- **Persistence:** MySQL
- **Asset tools:** GIMP, Aseprite (50+ custom sprites)

## Team
team of 4 — systems design, asset pipeline, integration.

## Build
Open `final task1.sln` in Visual Studio 2022 with SFML installed.
