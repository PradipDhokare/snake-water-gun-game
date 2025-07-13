# 🐍 Snake Water Gun Game (Python Mini Project)

This is a simple command-line based Snake Water Gun game in Python, similar to the classic Rock Paper Scissors.

## 🚀 How to Play:
- Computer randomly selects: Snake 🐍, Water 💧, or Gun 🔫
- You (the user) also choose one.
- The rules decide the winner:
  - Snake drinks Water → Snake wins
  - Water drowns Gun → Water wins
  - Gun kills Snake → Gun wins

## 📜 Rules:
- s = Snake
- w = Water
- g = Gun

### Winning Logic:
| Player | Computer | Result     |
|--------|----------|------------|
| s      | w        | Player wins|
| w      | g        | Player wins|
| g      | s        | Player wins|
| Same   | Same     | Tie        |
| Others |          | Computer wins|

## 💻 Run the game:

python snake_water_gun.py
