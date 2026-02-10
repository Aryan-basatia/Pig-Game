# Pig Game 🎲

A fun and interactive dice game built with HTML, CSS, and JavaScript. Players take turns rolling a dice and accumulating points, with the goal of reaching 100 points first!

## 🎮 Live Demo

Play the game here: [Pig Game](https://pig-game-200.netlify.app/)

## 📋 Table of Contents

- [About the Game](#about-the-game)
- [Features](#features)
- [How to Play](#how-to-play)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## 📖 About the Game

The Pig Game is a classic dice game where two players compete against each other. The objective is to be the first player to reach 100 points. Players must decide when to hold their score or continue rolling the dice for more points—but watch out! Rolling a 1 means you lose all your current round points.

## ✨ Features

- 🎯 Two-player gameplay
- 🎲 Realistic dice rolling mechanics
- 💾 Real-time score tracking for both players
- 🔄 Turn-based system with automatic turn switching
- ⚠️ Risk/reward gameplay mechanics
- 🎨 Responsive and intuitive user interface
- 📱 Works on desktop and mobile devices
- 🔄 New Game button to restart anytime

## 🎮 How to Play

1. **Starting the Game**: The first player (Player 1) begins the game.

2. **Taking a Turn**:
   - Click the "Roll Dice" button to roll the dice
   - If you roll a 2-6: The number is added to your current round score
   - If you roll a 1: Your current round score becomes 0 and it's the next player's turn

3. **Holding Your Score**:
   - Click "Hold" to add your current round score to your total score
   - Your turn automatically passes to the next player

4. **Winning**:
   - The first player to reach 100 points wins the game!

## 💻 Installation

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge, etc.)
- No additional software or dependencies required

### Steps

1. Clone the repository:
```bash
git clone https://github.com/Aryan-basatia/Pig-Game.git
cd Pig-Game
```

2. Open the game in your browser:
```bash
# Option 1: Double-click index.html
# Option 2: Use a live server extension in your code editor
# Option 3: Deploy to a web hosting service
```

## 🚀 Usage

1. Open `index.html` in your web browser
2. Click "New Game" to start
3. Player 1 begins by rolling the dice
4. Use the "Roll Dice" and "Hold" buttons to play
5. The game announces the winner when someone reaches 100 points
6. Click "New Game" to play again

## 📁 Project Structure

```
Pig-Game/
├── index.html          # Main HTML file
├── style.css           # Styling and layout
├── script.js           # Game logic and functionality
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5** - Structure and markup
- **CSS3** - Styling and responsive design
- **JavaScript (Vanilla)** - Game logic and interactivity
- **Netlify** - Hosting and deployment

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeatureName`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature/YourFeatureName`)
6. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License.

---

**Enjoy the game and happy rolling! 🎲**