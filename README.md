# Blackjack Game

This project is a Java implementation of the popular casino card game Blackjack. The objective of the game is to get a hand value as close to 21 as possible without exceeding it. Players compete against a computer-controlled dealer.

## Features

- Interactive gameplay with console-based user interface.
- Standard rules of Blackjack.
- Real-time display of each player's hand and score.
- Automatic evaluation of winning and losing hands.
- Simulated deck of cards with shuffling functionality.

## Prerequisites

- Java Development Kit (JDK) installed on your machine.
- Java's Swing library
- ant for java

## Installation

1. Clone this repository to your local machine. ``git clone https://github.com/ElephantMan10/blackjack``
2. Navigate to the project directory. ``cd blackjack``
3. Compile the source code. ``ant``
4. Run the game. ``ant run``

## Gameplay

- Each player starts with two cards facing up, while the dealer has one card facing up and one card facing down.
- Players take turns deciding whether to hit (draw a card) or stand (end their turn).
- The objective is to have a hand value as close to 21 as possible without exceeding it.
- The dealer follows a set of predefined rules for drawing cards.
- The game ends when all players have completed their turns, and the dealer reveals their facedown card.
- Winning and losing hands are evaluated based on hand values and any additional game rules, such as blackjack (an initial hand value of 21).
- The game prompts players to play again or exit.
