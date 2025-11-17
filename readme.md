# 🎮 Danger Zone – 2 Players ⚡
A fast-paced 2-player survival game built using **Python + Pygame**.  
Avoid the moving danger zone, collect power-ups, and outscore your opponent!

---

## 📌 How to Play

### 🎯 Objective
Stay alive longer than your opponent and earn the highest score before the timer ends.

---

## 🧍‍♂️ Player Controls

### Player 1 (Arrow Keys)
| Action | Key |
|-------|-----|
| Move Up | ⬆️ |
| Move Down | ⬇️ |
| Move Left | ⬅️ |
| Move Right | ➡️ |

### Player 2 (WASD Keys)
| Action | Key |
|-------|-----|
| Move Up | W |
| Move Down | S |
| Move Left | A |
| Move Right | D |

---

## 🏁 Gameplay Rules

### 1. Scoring
- Players earn **+1 point** every time they move.
- No points awarded for standing still.

---

## ⚠️ Danger Zone
- A red square randomly moves around the map every **3 seconds**.
- Entering the danger zone:
  - Player turns **Red**
  - Player **loses 1 life**
  - Player respawns at starting position

Each player has **3 lives**.

---

## ⭐ Power-Ups

Power-ups randomly appear and disappear after a few seconds.

### Types of Power-Ups
| Power-Up | Color | Effect |
|----------|--------|--------|
| Speed Boost | 🔵 Blue | Speed increases from 5 → 8 for 5 seconds |
| Immunity Shield | 🟧 Orange | Player becomes immune to the danger zone for 5 seconds |

Collect a power-up by moving into its box.

---

## 🧭 Color Indicators
- 🟩 **Green** – Safe zone  
- 🟨 **Yellow** – Right side of screen  
- 🟥 **Red** – Inside danger zone  
- 🔵/🟧 – Power-ups

---

## ⏳ Timer
- Each match lasts **30 seconds**.
- When time is up, the player with the highest score wins.

---

## ❤️ Lives
- Both players start with **3 lives**.
- Lose a life by entering the danger zone.
- If a player’s lives reach 0 → the opponent wins immediately.

---

## 🥇 Winning Conditions
The game ends when:

1. A player loses all 3 lives → **Other player wins**, OR  
2. Timer reaches 0 → **Higher score wins**, OR  
3. If both scores match → **Draw**

---

## ⏸️ Pause Game
- Press **P** to pause.
- Press **P** again to resume gameplay.

---

## 🔚 Game Over Screen
Displays:
- Winner’s name  
- Both players’ final scores  
- Options:
  - Press **R** → Restart  
  - Press **ESC** → Quit the game

---

## ▶️ How to Run

### Step 1: Install Pygame
```bash
pip install pygame

#https://youtu.be/MJGtOTn0gUk?si=eag3wJG1uLYB2Uo2
