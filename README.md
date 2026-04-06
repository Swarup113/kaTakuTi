# kaTakuTi – Battle in Squares

### *A modern, responsive multi-grid strategy game*

Experience the classic Tic‑Tac‑Toe concept on a larger scale. Choose between 3×3, 5×5, or 7×7 grids, each with its own winning line length. Smooth animations, a neon UI, and local two‑player battles make kaTakuTi a fresh take on an old favorite – built with pure HTML, CSS, and JavaScript.

---

## Overview

**kaTakuTi** is a two‑player local (hot‑seat) game where players take turns placing their marks (X and O) on a grid. Unlike standard Tic‑Tac‑Toe, the win condition changes with the grid size:

- **3×3 grid** → get **3** consecutive marks in a row, column, or diagonal.
- **5×5 grid** → get **4** consecutive marks.
- **7×7 grid** → get **5** consecutive marks.

The game keeps track of scores across multiple rounds. Players can start a new game, finish the current game, or quit at any time. The interface is fully responsive and works on desktops, tablets, and mobile devices.

---

## Live Demo

Play the game directly in your browser:  
 **https://swarup113.github.io/kaTakuTi/**

---

## Features

- **Three grid sizes** – 3×3, 5×5, and 7×7 with dynamic win conditions.
- **Local two‑player mode** – pass the device and take turns.
- **Score tracking** – keeps score across multiple rounds until you quit or start a new game.
- **Clean neon UI** – cyan and coral themes with smooth transitions and hover effects.
- **Fully responsive** – the grid scales gracefully on any screen size.
- **Game control options** – back button, finish game, resume, new game, and quit.
- **Modal dialogs** – clear rules, game over messages, and confirmation dialogs.

---

## How to Play / Rules

1. **Setup** – enter optional player names (or leave default). Choose a grid size (3×3, 5×5, or 7×7).
2. **Start the game** – Player 1 (X, cyan) goes first.
3. **Take turns** – click on an empty cell to place your mark.
4. **Win condition** – the first player to get the required number of consecutive marks in a row, column, or diagonal wins the round.
   - 3×3 grid → 3 in a row
   - 5×5 grid → 4 in a row
   - 7×7 grid → 5 in a row
5. **Scoring** – the winner of the round earns 1 point. The game continues with the same grid size until you choose to start a new game or quit.
6. **Draw** – if the grid fills up with no winner, the round ends with no points awarded.
7. **Continue playing** – after a win or draw, the next round starts automatically. Scores persist across rounds.

Use the **Finish Game** button to end the session, or **Back** to return to the setup screen.

---

## Tech Used

- **HTML5** – semantic structure, modal dialogs, responsive meta tags.
- **CSS3** – CSS Grid for dynamic board layout, Flexbox for alignment, keyframe animations, glass‑morphism effects.
- **JavaScript (ES6)** – game state management, win detection algorithms, event handling, dynamic grid generation.
- **Google Fonts** – Orbitron (headings) and Space Grotesk (body) for a futuristic look.

---

## License

MIT License

---

