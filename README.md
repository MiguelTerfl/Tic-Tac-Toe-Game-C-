# Tic-Tac-Toe Game

A implementation of the classic Tic-Tac-Toe game using C#. This project is a console application that allows two players to play against each other. 

## Features

- Two-player mode (Player 1 vs Player 2)
- Interactive console-based interface
- Automatic detection of win or draw conditions

## Getting Started

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) installed on your machine.

### Running the Game

1. Clone the repository:

  ```bash
  git clone https://github.com/yourusername/tic-tac-toe.git
  cd tic-tac-toe
  ```

2. Build and run the application:

  ```bash
  dotnet run
  ```

3. Follow the on-screen instructions to play the game.

How to Play
- The game board is numbered from 1 to 9, with each number corresponding to a cell.
- Players take turns to choose a cell by entering its number.
- The first player to get three of their marks (X or O) in a row, column, or diagonal wins the game.
- If all cells are filled and no player has won, the game ends in a tie.

Example

  ```bash
  1|2|3
  ------
  4|5|6
  ------
  7|8|9

  Player 1 turn!
  ```

Players will input the number corresponding to the cell where they want to place their mark. The grid will update, and the game will continue until there's a winner or a tie.
