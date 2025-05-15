# Mobile Snake Game

A mobile-friendly snake game with touch controls and a dark theme.

## Features
- Mobile-optimized with touch controls
- Dark theme with grid background
- Score tracking
- Restart functionality
- Responsive design

## How to Test

1. Host the files using a local server. You can use one of these methods:

   Using Python 3:
   ```bash
   python -m http.server 8000
   ```

   Using Node.js (with `http-server` package):
   ```bash
   npx http-server
   ```

2. Access the game on your mobile device:
   - Make sure your computer and phone are on the same network
   - Find your computer's local IP address
   - On your phone, open a browser and go to `http://[YOUR_IP_ADDRESS]:8000`

## Controls
- Swipe up, down, left, or right to change the snake's direction
- Tap the "Restart Game" button to start a new game after game over

## Game Rules
- Guide the snake to eat the food (grey squares)
- Each food item increases your score by 10 points
- Game ends if the snake hits the wall or itself
- Use the restart button to play again 
