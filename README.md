# Rock-Paper-Scissors Game (HTML + CSS Only)

This is a **Rock-Paper-Scissors** game built using **only HTML and CSS**. It features interactive hand animations and win/loss detection—all without JavaScript.

## 🎮 How to Play

1. The game UI displays two animated hands: one for the **Computer** and one for the **User**.
2. Select your move (✊ Rock, 🖐️ Paper, ✌ Scissors) using the buttons.
3. Based on the selected radio button, the game automatically animates the hands and displays the result (Win, Lose, or Tie).
4. Click the **Refresh Round** button to play again.

## 💡 Features

- Fully functional without JavaScript
- Smooth hand animations using CSS keyframes
- Displays results dynamically with `:checked` selectors
- Responsive layout with clean, simple design

## 📁 Project Structure


## 🧩 How It Works

- The game uses 9 radio inputs (one for each possible combination of choices).
- Each input has a corresponding `label` styled as Rock, Paper, or Scissors.
- CSS rules trigger different hand styles and outcomes using the `:checked` pseudo-class.
- The result is displayed using `::before` content on `h2` elements.

## 🚀 Getting Started

1. Download the project files.
2. Open `rock.html` in any modern browser.
3. Enjoy playing Rock-Paper-Scissors!

## 👨‍💻 Credits

Created by **Coding Torque**  
Modified and used for educational/demo purposes.

## 📜 License

This project is open for personal and educational use.
