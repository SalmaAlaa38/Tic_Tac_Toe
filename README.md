# Tic-Tac-Toe Game

## Overview
This repository contains a **Tic-Tac-Toe** game built with React. It is an interactive, dynamic implementation of the classic game, featuring gameplay enhancements and an intuitive user interface.

## Features
- **Play Tic-Tac-Toe**: Engage in a two-player game of tic-tac-toe.
- **Winning Detection**: The game indicates when a player has won by forming a line (horizontal, vertical, or diagonal).
- **Game History**: Tracks the history of moves as the game progresses.
- **Time Travel**: Allows players to review the game’s history and view previous versions of the game board.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd tic-tac-toe
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Usage
1. Start the development server:
   ```bash
   npm start
   ```
2. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```
3. Enjoy playing the game!

## How to Play
1. The game is played by two players, **X** and **O**.
2. Take turns clicking on empty squares to place your mark.
3. The game ends when:
   - A player forms a line of three marks (horizontal, vertical, or diagonal).
   - All squares are filled without a winner (draw).
4. Use the history list to revisit earlier states of the game by clicking the corresponding button.

## Project Structure
- **`src`**: Contains the source code for the application.
  - **`Game.js`**: Main component managing the game logic.
  - **`Board.js`**: Component rendering the tic-tac-toe grid.
  - **`Square.js`**: Component representing an individual square.
- **`public`**: Contains static files and the `index.html`.

## Technologies Used
- **React**: Frontend library for building the UI.
- **JavaScript (ES6)**: Core programming language.
- **CSS**: Styling for the game interface.

## Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to your forked repository.
4. Submit a pull request describing your changes.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
Inspired by the official React tutorial for building a tic-tac-toe game.

