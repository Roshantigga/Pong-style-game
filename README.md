#  Raylib Pong Game

Welcome to a classic **Pong-style game** built using [Raylib](https://www.raylib.com/)!  
Control the paddle, hit the ball, beat the CPU — and enjoy the retro-inspired colors.

---

##  Gameplay

- The **player** controls the paddle on the right using the `UP` and `DOWN` arrow keys.
- The **CPU** paddle is on the left and automatically tracks the ball.
- If the ball passes your paddle — CPU scores.
- If the ball passes CPU — you score.
- First to keep playing... wins your own high score 😎

---

##  Features

- 🚀 Smooth 60 FPS gameplay
-  Retro green-themed visuals with custom colors
-  Basic AI-controlled opponent
-  Ball resets after each goal with random direction
-  Collision detection and movement constraints

---

##  Built With

- **C++**
- **[Raylib](https://www.raylib.com/)** - a simple and easy-to-use library to enjoy game programming

---

##  How to Run

###  Prerequisites:
- Raylib installed and linked correctly
- C++ compiler (like `g++` or `clang++`)
- OS: Windows / Linux / Mac

---

### 🔧 Compilation Command (example for Windows using MinGW):
```bash
g++ main.cpp -o pong_game -lraylib -lwinmm -lgdi32

## or
simplly run .\main in your terminal
