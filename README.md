# Tic-Tac-Toe
A responsive web-based Tic Tac Toe game that supports two-player mode (Player X and Player O), keeps track of scores, handles draws, highlights winning moves, and allows players to reset or start a new game.

---

##  Features

-  Two-player mode (Player X vs Player O)
-  Real-time win and draw detection
-  Scoreboard to track wins and draws
-  Smooth animations and visual feedback
-  Fully responsive and mobile-friendly
-  Reset and new game functionality
-  Winning cells get highlighted
-  Disabled interaction on filled cells

---

##  Workflow

1. **Game Initialization**  
   The board loads with 9 clickable cells. Player X starts by default.

2. **Gameplay Loop**  
   - Players alternate turns.
   - Clicked cells are filled with the current player's symbol.
   - Win conditions are checked after every move.
   - If a win or draw is detected:
     - Winner is announced and cells are disabled.
     - Scores are updated accordingly.

3. **Control Options**  
   - **Reset Game**: Clears the board and keeps scores.
   - **New Game**: Clears the board and resets scores to 0.

4. **UI Behavior**  
   - Hover effects on cells
   - Animated winning line
   - Dynamic text showing the current player or result

---

##  Technology Used

 **HTML5**: Structure and game layout      
 **CSS3**: Styling, responsiveness, animations
 **JavaScript**: Game logic and interactivity 

---

##  Future Work

Here are a few enhancements planned for future versions:

-  Single-player mode with basic AI
-  Dark mode toggle
-  Sound effects for clicks, wins, and draws
-  Score persistence using `localStorage`
-  Online multiplayer support
-  Leaderboard or match history

---

##  Author

**Harshit Khanna**  

---
