# Tic Tac Toe Game

A simple Tic Tac Toe game built with React, where two players can take turns to place their marks (X or O) on a 3x3 grid. The goal is to align three symbols in a row, column, or diagonal. This project demonstrates fundamental React skills such as component-based structure, state management, and event handling.

## Features

- **Two-player mode**: Players X and O alternate turns.
- **Game Over conditions**: Displays winner or draw when the game ends.
- **Log of moves**: Displays a history of moves made during the game.
- **Editable player names**: Players can change their names during the game.
- **Responsive layout**: The game works on various screen sizes.

## Demo

Here is a screenshot of the game:

![Tic Tac Toe Screenshot](https://github.com/macettiandrea/React-Tic-Tac-Toe/raw/main/screenshots/Screenshot.png)

## How to Install and Run the Project

1. **Clone the repository**:

   ```bash
   git clone https://github.com/macettiandrea/React-Tic-Tac-Toe.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd React-Tic-Tac-Toe
   ```

3. **Install dependencies**:

   Make sure you have Node.js installed. Then run:

   ```bash
   npm install
   ```

4. **Run the application**:

   Use the following command to start the development server:

   ```bash
   npm run dev
   ```

5. **Access the application**:

   Open your browser and go to `http://localhost:3000` to play the game.

## Project Structure

- **App.jsx**: The main component that manages game logic, state, and renders the players, game board, and log.
- **components/Player.jsx**: Handles player name changes and tracks the active player.
- **components/GameBoard.jsx**: Renders the game board and handles square selection logic.
- **components/GameOver.jsx**: Displays the game over screen with the winner or draw message.
- **components/Log.jsx**: Keeps track of player moves and displays the history of turns.
- **components/winning_combinations.js**: Contains the winning combinations for Tic Tac Toe.

## Known Issues

- **Move repetition**: Players cannot select the same square twice, but no AI or multiplayer support is currently implemented.
- **Edge cases**: The game only supports two human players locally.

## Future Improvements

- Add an AI opponent for single-player mode.
- Implement multiplayer functionality via WebSockets or other real-time technology.
- Enhance the UI with animations or improved styling.

## License

This project is open for educational purposes, but feel free to modify it for your personal use. If you're using this code, consider acknowledging the original author.
