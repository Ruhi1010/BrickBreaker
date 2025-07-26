# 🧱 Brick Breaker 

A modern, visually enhanced **Brick Breaker game** built with **Python** and **Pygame**.

---

## 🎮 Game Overview

**Brick Breaker Extreme** features:
- Colorful bricks with a 3D look
- A glowing ball with trail effects
- A shiny paddle with gradient
- Particle explosion effects
- Background star field with gradient sky
- Win and Game Over screens with UI overlay

---

## 🕹 Controls

| Key         | Action                    |
|-------------|---------------------------|
| ← / →       | Move paddle left / right  |
| R           | Restart after game over   |
| Q           | Quit the game             |

---

## 🧩 Features Breakdown

### 1. Constants & Initialization
- Sets screen size: `800x600`
- Initializes color palette for bricks, paddle, background.

### 2. `Particle` Class
- Small dots created when a brick is destroyed.
- Gravity pulls them down.
- Fades out over time.

### 3. `Paddle` Class
- Controlled by arrow keys.
- Gradient fill with white border.
- Clamped to screen width.

### 4. `Ball` Class
- Bounces off walls, paddle, bricks.
- Changes direction on collision.
- Includes glowing and trailing visual effects.

### 5. `Brick` Class
- Grid of colored blocks.
- Destroyed on collision with ball.
- Gives points; higher bricks yield more points.

### 6. `Game` Class
Manages:
- Object creation (`reset_game`)
- Physics and collision (`handle_collisions`)
- UI, drawing, game state
- Main loop (`run`)

---

## 🖼 Game Screens

### 🟢 Gameplay
- Move paddle to bounce the ball.
- Break all bricks to win.

### 🔴 Game Over
- Ball falls below screen 3 times = Game Over.
- Restart or Quit options.

### 🎉 Victory
- All bricks broken = You Win!

---

## 🛠 Installation & Running

### Prerequisites:
- Python 3.x
- Pygame installed via pip:
```bash
pip install pygame
python your_script_name.py
```
___
