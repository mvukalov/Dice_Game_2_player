# 🎲 Dice Game – 2 Player

A simple two-player dice game built using **JavaScript, HTML, and CSS**.

This project was created as a practice project to improve understanding of core JavaScript concepts such as DOM manipulation, event handling, and basic game logic implementation.

---

## 🚀 Live Demo

👉 https://dice-game-2player-mv.netlify.app/

---

## ✨ Features

- Two-player turn-based gameplay  
- Random dice generation  
- Current score tracking  
- Total score tracking  
- "Hold" functionality  
- Automatic player switching  
- Losing current score when rolling number 1  
- Win condition detection  
- New Game reset functionality  
- Clean and responsive user interface  

---

## 🛠 Tech Stack

### Frontend
- HTML5  
- CSS3  
- JavaScript (Vanilla JS)

### Tools
- Git  
- GitHub  

---

## 🎮 Game Rules

1. The game is played by **two players**.
2. Players take turns rolling a dice.
3. If a player rolls a number **greater than 1**:
   - The number is added to their current score.
   - They can choose to roll again or hold.
4. If a player rolls **1**:
   - They lose all points accumulated in the current round.
   - The turn switches to the other player.
5. If the player chooses to **Hold**:
   - The current score is added to their total score.
   - The turn switches to the other player.
6. The first player to reach the predefined winning score wins the game.

---

## ⚙️ How It Works

- The game logic is written entirely in JavaScript.
- Event listeners are used to detect button clicks (Roll, Hold, New Game).
- Random dice numbers are generated using `Math.random()`.
- The DOM is updated dynamically to reflect score changes and active player.
- Conditional logic controls:
  - Score accumulation
  - Player switching
  - Win detection
- When the game ends, the winning player is highlighted.
- Clicking "New Game" resets all values and starts a fresh game session.

---

## 📦 Run Locally

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
```

2. Navigate into the project folder:

```bash
cd your-repository-name
```

3. Open `index.html` in your browser.

No additional dependencies are required.

---

## 📁 Project Structure

```
Dice-Game/
│
├── index.html     # Main HTML structure
├── style.css      # Styling and layout
├── script.js      # Game logic
└── README.md      # Project documentation
```

---

## 🧠 Key Concepts Practiced

- DOM manipulation  
- Event handling  
- Functions  
- Conditional logic  
- State management  
- Basic game architecture  
- Code organization  

---

## 👤 Author

Martin Vukalović


---

## 📄 License

This project is created for educational and portfolio purposes.
