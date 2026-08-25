# Pong Game

A classic Pong game built with HTML, CSS, and JavaScript. Play against a computer AI opponent!

## Features

✨ **Player vs Computer AI** - Challenge the computer opponent

🎮 **Dual Control Options** - Control the left paddle using either your mouse or arrow keys

⚽ **Dynamic Ball Physics** - Ball bounces off paddles, walls, and includes spin based on paddle hit position

🏐 **Collision Detection** - Full collision detection for paddles and walls

📊 **Live Scoreboard** - Real-time score tracking for both player and computer

⏸️ **Pause/Resume** - Press SPACEBAR to pause or resume the game

🎨 **Modern UI** - Sleek design with green neon aesthetics

## How to Play

1. Open `index.html` in your web browser
2. **Start the game** by pressing SPACEBAR
3. **Control the left paddle** using:
   - 🖱️ **Mouse**: Move your mouse up and down
   - ⬆️ ⬇️ **Arrow Keys**: Press Up/Down arrow keys
4. **Objective**: Keep the ball from going past your paddle while trying to get it past the computer's paddle
5. **Pause/Resume**: Press SPACEBAR anytime to pause or resume

## Game Mechanics

- **Paddles**: Located on the left (player) and right (computer) sides of the screen
- **Ball**: Bounces off paddles and walls. Speed and angle vary based on where it hits the paddle
- **Scoring**: Each time the opponent fails to return the ball, you score a point
- **AI Difficulty**: The computer AI has a balanced difficulty level with a slight reaction delay

## Files

- `index.html` - Main HTML file with game canvas and UI
- `styles.css` - Styling with modern design and animations
- `game.js` - Game logic including ball physics, collision detection, and AI

## Technical Details

- **Canvas API** - Used for rendering game elements
- **Collision Detection** - Rectangle-circle collision for paddle hits, boundary checking for walls
- **AI Algorithm** - Predictive movement based on ball position with configurable difficulty
- **Input Handling** - Real-time keyboard and mouse event listeners

## Browser Compatibility

Works on all modern browsers that support HTML5 Canvas API (Chrome, Firefox, Safari, Edge)

## License

Free to use and modify
