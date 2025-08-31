#  Game Hub – Tic Tac Toe & Snake and Ladder

##  Objective  
The objective of this project is to build a **Java-based Game Hub** where users can play **Tic Tac Toe** or **Snake & Ladder**.  
It demonstrates concepts of **OOP, data structures, control flow, and randomization** in Java.

---

##  Features  

### Game Hub (Menu Driven)  
- Lets players choose **Tic Tac Toe**, **Snake & Ladder**, or **Exit**  

### Tic Tac Toe  
- Classic **3×3 board game**  
- Two players (X and O) take turns  
- Checks for **winner/draw**  
- Stores complete **move history**  

### Snake & Ladder  
- Two players roll dice to move from **1 → 100**  
- **Snakes** pull players down   
- **Ladders** push players up   
- Dice rolls are **randomized**  
- Complete move history is stored  

---

##  Concepts Used  

- **OOP Principles**  
  - Classes → `Move`, `MoveList`, `TicTacToe`, `SnakeAndLadder`, `HubGame`  
  - Encapsulation → Board and moves stored as private  
  - Composition → Both games use `MoveList`  
  - Abstraction → Each game exposes a `play()` method  

- **Game Logic**  
  - Loops for turns  
  - If–else conditions for validation  
  - Random number generation for dice  

- **Data Structures**  
  - `char[][]` → Tic Tac Toe board  
  - `ArrayList` → To store moves  

---

##  Example – Snake & Ladder Logic  

```java
int[] snakes = {16, 48, 62, 64, 93, 95, 98};
int[] snakeTo = {6, 26, 18, 60, 68, 24, 78};
int[] ladders = {1, 4, 9, 21, 28, 51, 72, 80};
int[] ladderTo = {38, 14, 31, 42, 84, 67, 91, 99};

##  Future Scope
- Add AI opponent and multiplayer mode  
- Create a simple GUI for better user interaction  
- Enable saving game progress and scores  

##  Future Scope
- Add AI opponent and multiplayer mode  
- Create a simple GUI for better user interaction  
- Enable saving game progress and scores  

##  Author
 R Rithanya  
 ravirithanya1@gmail.com  

If this project added value to your learning or work, I’d really appreciate your support by giving it a ⭐ on GitHub.

##  Author
 R Rithanya  
 ravirithanya1@gmail.com  

If this project added value to your learning or work, I’d really appreciate your support by giving it a ⭐ on GitHub.

