# NisheshChauhan_Task(30)

A lot of modules inspired by other creators and code modules...

## Summary
This project is a fully functional chess game built with React and Vite. It offers a playable chessboard with legal move validation, turn-based gameplay, check/checkmate detection, and match timing features, making it a complete browser-based chess application.

## What it Does?
- Provides a complete 8x8 chess board for two players.
- Allows legal move generation and validation for all standard chess pieces.
- Detects check, checkmate, and stalemate scenarios.
- Supports castling, en passant, and pawn promotion.
- Keeps move history and enables undo actions during gameplay.
- Includes player timers with selectable time controls.
- Saves the current game state in the browser for continuity.
- Offers light/dark theme switching for a better user experience.

## Project Structure
- `src/App.jsx` – main app logic and interactive gameplay UI.
- `src/chessEngine.js` – chess rules, move generation, and validation logic.
- `src/components/` – reusable UI components like the board, trays, move table, and promotion modal.
- `src/utils/` – helper functions such as sound utilities.
- `src/assets/` – project images and static assets.
- `public/` – public static files.
- `index.html` – application entry file.
- `package.json` – project scripts and dependencies.

## How to Run?
1. Open a terminal in the project folder.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open the local URL shown in the terminal in your browser.
5. To create a production build, run:
   ```bash
   npm run build
   ```

## Technologies Used
- React
- Vite
- JavaScript
- CSS
- Tailwind CSS

## Author
Nishesh Chauhan