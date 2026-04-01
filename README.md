# Hidden Card Game - GitHub Pages Version

This is a client-side JavaScript implementation of the Hidden Card Game, originally a Flask app. It has been converted to run entirely in the browser for deployment on GitHub Pages.

## How to Deploy

1. Upload all files in this folder to a GitHub repository.
2. Enable GitHub Pages in the repository settings.
3. The game will be playable at your GitHub Pages URL.

## Game Description

This is a logic puzzle game where players have hidden cards and ask questions about sets of cards to deduce what the hidden card is. The game features:

- 3 players (you + 2 bots)
- 10 cards total (1-10)
- Each player gets 3 cards
- 1 hidden card
- 5 possible query sets

The bots use information theory to make optimal queries.

## Features

- Random or custom card distributions
- Two strategies: Information Gain or Shannon Entropy
- Step-by-step rewind functionality
- Real-time probability distributions
- Query scoring and recommendations

## Files

- `index.html` - The complete game application