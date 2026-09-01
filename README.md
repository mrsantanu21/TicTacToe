# TicTacToe
Tic Tac Toe — Python Web App

A two-player Tic-Tac-Toe game built entirely in Python and deployed as a web application using Streamlit.

About

This project was built for a university assignment requiring a Tic-Tac-Toe game implemented in Python and deployed on the web.The game logic, state management, and user interface are all written in Python.

Features
Classic 3×3 Tic-Tac-Toe for two players (X and O)
Turn-based play with automatic win and draw detection
Highlights the winning line when a player wins
Persistent score tracking across rounds
"New Game" to start a fresh round while keeping the score
"Reset Scores" to clear the scoreboard
Sound and theme (Light/Dark) settings
Runs in any browser once deployed no installation needed for players
Design

The interface follows a minimalist, dashboard-style layout inspired by modern mobile app design, arranged into three columns:

Left column — an intro card with the game title and tagline, and a score card showing each player's wins.
Middle column — the game mode card, the main 3×3 board, and the "New Game" button.
Right column — a players card showing whose turn it is, a game status card announcing turns/wins/draws, and a settings card.

Visual style:

A warm, neutral color palette: beige background, cream rounded cards, sage green as the primary accent, and muted brown as a secondary accent.
Large rounded corner "cards" group related information, similar to a mobile app UI, instead of a plain traditional window.
X marks are colored in dark charcoal and O marks in sage green, so the two players are visually distinct at a glance.
The winning three cells are highlighted in a muted brown accent color when the game ends in a win.
Buttons use rounded, flat styling rather than default browser/OS button chrome, keeping the look consistent and clean.

The goal of the design was to make the game feel calm, modern, and easy to read, while keeping the underlying implementation simple and entirely in Python.
