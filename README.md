# Gem-Game---python
Overview
This project is a turn-based strategy game developed using Pygame, where players can compete against each other or against AI-controlled bots. The game features a grid-based board where players take turns placing pieces, with various enhancements for an engaging experience.
Features
Two Player Modes: Play against another human or challenge an AI opponent.
Dynamic Game Board: A 5x6 grid where players strategically place their pieces.
Animated Piece Drops: Visual effects when pieces are placed on the board.
Particle Effects: Adds flair to the gameplay with visual particle animations.
Sound Effects: Audio feedback for moves and winning actions.
Score Tracking: Keeps track of each player's score throughout the game.
Turn Timer: Each player has a limited time to make their move.
Overflow Mechanic: A unique gameplay feature that alters the board state.
Getting Started
Prerequisites
To run this game, ensure you have Pygame installed. You can install it using pip:
bash
pip install pygame

Running the Game
Once Pygame is installed, you can run the game by executing the following command in your terminal:
bash
python game.py

Game Structure
Classes
Dropdown: Handles the creation of dropdown menus for player selection.
Board: Manages the game state, including valid moves and win conditions.
Game Logic
The game alternates turns between players, checks for valid moves, and determines win conditions. Special effects like animations and sound enhance the user experience.
Assets
The gem images used in the game are sourced from OpenGameArt.org, specifically from the following links:
Rotating Crystal Animation by qubodup
Licensed under CC BY 3.0
Acknowledgments
Catherine Leung: For providing the framework and guidance for this assignment.
OpenGameArt.org: For the assets used in the game.
Enjoy playing and feel free to explore the code to see how everything works!
