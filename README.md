# Blackjack Game

This Python project is a simple text-based Blackjack game where you can play against the computer dealer in the console. The game is implemented in Python and showcases object-oriented programming principles. Here's a brief overview of how the game works and how you can run it on your own machine.

## How It Works

The game consists of several classes that represent the main components of a Blackjack game:

- `Card`: Represents a single card with a suit and rank.
- `Deck`: Represents a deck of cards. It can shuffle the deck and deal cards.
- `Hand`: Represents a hand of cards for either a player or the dealer. It can calculate the value of the hand, check for blackjack, and display the hand.
- `Game`: Controls the flow of the game, including dealing cards, handling player and dealer actions, and determining the outcome of each game.

Players can decide how many games they want to play in a session. During each game, the player can choose to "Hit" to take another card or "Stand" to hold their current hand. The dealer must hit if their hand is below 17. The game checks for wins, losses, and ties based on the rules of Blackjack.

## Features

- Play multiple games of Blackjack in one session.
- Simple and intuitive text-based user interface.
- Automatic handling of card shuffling, dealing, and hand value calculation.
- Checks for Blackjack and bust conditions for both player and dealer.

## Requirements

- Python 3.x

## Running the Game

1. Ensure you have Python installed on your computer.
2. Copy the code into a file named `blackjack.py`.
3. Open your terminal or command prompt.
4. Navigate to the directory where you saved `blackjack.py`.
5. Run the game with the command: `python blackjack.py`
6. Follow the on-screen prompts to play the game.

## How to Play

- At the start of each session, you'll be asked how many games you want to play.
- For each game, you and the dealer will be dealt two cards. One of the dealer's cards is hidden until your turn ends.
- Choose "Hit" to receive another card or "Stand" to end your turn.
- After your turn ends, the dealer's hidden card is revealed, and the dealer may take additional cards based on the game rules.
- The game compares the values of your hand and the dealer's hand to determine the winner.
- Play continues until all games are completed.

## Exiting the Game

- You can exit the game anytime by closing the terminal or command prompt window.
- After completing the specified number of games, you'll be prompted to press any key to exit.

Enjoy playing Blackjack!
