# README for Blackjack Game

## Overview
This Python script is a simple yet engaging text-based version of the popular card game, Blackjack (also known as 21). The game is played against a computer opponent and includes features like card dealing, score calculation, and win/loss determination based on Blackjack rules.

## Features
- **Random Card Dealing**: Cards are dealt randomly to both the player and the computer.
- **Score Calculation**: The script calculates the score of the player and the computer's hand.
- **Game Decisions**: The player can choose to get another card or hold their current hand.
- **Win/Loss Determination**: The game determines the outcome (win, lose, draw) based on the final scores and Blackjack rules.

## How to Play
1. Run the script.
2. Respond to the prompt: "Do you want to play a game of Blackjack? Type 'y' or 'n': " with 'y' to start the game.
3. You will be dealt two cards initially, and the computer will have one card revealed.
4. You can choose to get another card ('y') or pass ('n').
5. The game ends when you pass, get a Blackjack, or exceed 21 points.
6. The computer plays its hand following the rules of Blackjack.
7. The final hands and scores are displayed, and the game announces the outcome.

## Functions
- `deal_card()`: Returns a random card from the deck.
- `calculate_score(cards)`: Calculates the score of a given hand.
- `compare(user_score, computer_score)`: Compares scores and determines the winner.
- `play_game()`: Contains the main game loop.

## Dependencies
- `random`: Used for random card dealing.

## Note
This game is for entertainment purposes and does not involve real money gambling.

---

Enjoy the game and may luck be in your favor!