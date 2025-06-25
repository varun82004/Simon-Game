## 🟢 Simon Game 🎮

A simple memory-based game inspired by the classic **Simon Electronic Game**. This interactive browser game challenges the player to repeat an ever-growing sequence of colors and sounds. Built using **HTML**, **CSS**, and **JavaScript** with a focus on clean design and core logic.

---

## 🚀 Features

- 🎨 Four colored buttons: Red, Blue, Green, Yellow
- 🧠 Pattern memory challenge
- 🔊 Sound effects for each button
- 💡 Visual animations on press
- 📈 Level-based progression
- ❌ Game over and restart functionality

---

## 🎯 How to Play

1. Press any key to start the game.
2. Watch the sequence of flashing buttons and sounds.
3. Repeat the sequence by clicking the buttons in the same order.
4. Each level adds one more color to the sequence.
5. Make a mistake? The game resets and displays "Game Over".

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML       | Page structure |
| CSS        | Styling & animations |
| JavaScript | Game logic and interactivity |
| jQuery     | DOM manipulation and event handling |

---

## 📂 Project Structure
├── index.html # Main HTML file
├── styles.css # Styling for the buttons and layout
├── game.js # Core game logic (nextSequence, user interaction, validation)
├── sounds/ # Audio files for button tones and error sound


---

## 📸 Screenshot

![Simon Game Screenshot](screenshot.png)  
![image](https://github.com/user-attachments/assets/f06f7307-7d5b-4562-a262-10ec2a3cd73a)


---

## 🔢 Game Logic Overview

- `nextSequence()`: Generates a random color and adds it to the game pattern.
- `checkAnswer()`: Compares user input with the game sequence.
- `startOver()`: Resets the game on failure.
- Sound and animation effects are used for feedback.

---

## 📊 Statistical/Programming Insight

- Random color generation uses `Math.floor(Math.random() * 4)` to sample uniformly from a discrete distribution.
- Time-series of player input can be modeled and analyzed for UX studies or skill progression tracking.
- Potential for AI agent simulation using Markov chains or memory models.

---

## 🧪 Possible Enhancements

- Add strict mode or timer
- Store high scores using `localStorage`
- Support mobile devices and touch events
- Add multiplayer or competitive mode
- Analyze input latency for skill tracking

---

## 💻 Live Demo

👉 [Play it here]([https://your-github-username.github.io/simon-game/]) *https://varun82004.github.io/Simon-Game/*

---

## 🧑‍💻 Author

**Varun Adhithya S** – @varun82004(https://github.com/varun82004)  
