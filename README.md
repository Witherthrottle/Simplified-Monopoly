

# Monopoly Lite in C++

A simplified version of Monopoly implemented in C++, featuring property management, player interactions, and a dynamic game board.

---

## Description

This project recreates a lightweight version of the classic board game Monopoly. Players roll dice, move around a game board, buy/sell properties, pay rent, draw cards, and manage their finances to stay in the game. The objective is to avoid bankruptcy and outlast your opponents.

---

## Features

- **Dynamic Game Board**: Includes property tiles, free parking, jail tiles, tax tiles, and chance/community chest cards.
- **Player Management**: Track player positions, finances, and owned properties.
- **Property Transactions**: Buy, sell, or pay rent based on the tile you land on.
- **Special Tiles**: Jail, free parking, tax, and card-drawing tiles add complexity to the game.
- **Card System**: Community Chest and Chance cards can alter the course of the game.
- **Bankruptcy Handling**: Players can sell properties to stay in the game or declare bankruptcy when out of options.

---

## How to Play

1. **Start the Game**:
   - Players are initialized with $1500 each.
   - The game board contains various tiles, including properties, taxes, jail, and special cards.

2. **Gameplay**:
   - Players take turns rolling dice to move around the board.
   - Actions are triggered based on the tile landed on:
     - Buy or pay rent for properties.
     - Pay taxes or draw cards.
     - Manage properties (sell/trade) to handle financial challenges.
   - Avoid bankruptcy to stay in the game.

3. **Winning**:
   - The game ends when all but one player are bankrupt.

---

## Setup and Compilation

### Prerequisites
- A C++ compiler (e.g., GCC, Clang, or Visual Studio)
- Standard Template Library (STL) support

### Compilation
To compile the game, use the following command:

```bash
g++ -o monopoly monopoly.cpp
```

### Run the Game
After successful compilation, run the executable:

```bash
./monopoly
```

---

## Gameplay Flow

1. **Player Turn**:
   - Roll dice to determine movement.
   - Perform actions based on the tile landed on.
   - Optionally sell properties or trade with other players.

2. **Tile Actions**:
   - **Property Tiles**: Buy, sell, or pay rent.
   - **Community Chest/Chance**: Draw cards that impact finances or movement.
   - **Jail**: Pay to exit or attempt a lucky roll.
   - **Tax Tiles**: Pay the specified amount or sell properties to cover costs.

3. **Player Bankruptcy**:
   - If a player’s money drops below zero and they have no properties to sell, they are declared bankrupt and removed from the game.

---

## File Structure

```plaintext
monopoly.cpp  # Main game implementation
```

---

## Contributing

Contributions are welcome! Please fork this repository, make changes, and submit a pull request. For significant changes, open an issue to discuss your ideas.

---


Let me know if you'd like adjustments or additional details in any section!
