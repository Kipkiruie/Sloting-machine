# Java Slots Game 🎰

Welcome to the **Java Slots Game**, a simple command-line slot machine game written in Java. Test your luck by spinning the slots and see if you can win big!

## Features
- Interactive betting system.
- Symbol-based slot machine with payouts based on matches.
- Ability to continue playing or exit after each round.
- Customizable balance and symbols.

## Symbols and Payouts
The slot machine features the following symbols and payouts:
- **⭐ (Star):**
  - Three in a row: Bet × 3
  - Two in a row: Bet × 2
- **🍀 (Clover):**
  - Three in a row: Bet × 4
  - Two in a row: Bet × 3
- **🥠 (Fortune Cookie):**
  - Three in a row: Bet × 5
  - Two in a row: Bet × 4
- **🥭 (Mango):**
  - Three in a row: Bet × 10
  - Two in a row: Bet × 5

## How to Play
1. Start the game with an initial balance of $100.
2. Place a bet between $1 and your current balance.
3. The slot machine spins and generates a row of 3 symbols.
4. If symbols match, you win based on the payout rules.
5. Decide whether to play again or exit the game.
6. The game ends when your balance reaches $0 or you choose to quit.

## Requirements
- Java Development Kit (JDK) version 8 or higher.

## How to Run
1. Compile the program:
   ```bash
   javac Main.java
