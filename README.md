# Modern Number Guessing Game 🎮

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Tech Stack](https://img.shields.io/badge/tech-HTML%2C%20CSS%2C%20JS-brightgreen)](./)

A classic number guessing game, fully refactored for modern web development. This project demonstrates best practices in vanilla JavaScript, including robust game logic, a clean user interface, and an excellent user experience. It serves as a great example of how to structure a DOM manipulation project cleanly and efficiently.

---

## 📸 Screenshot

<img width="1791" height="880" alt="image" src="https://github.com/user-attachments/assets/8dea3e38-3fbf-4119-af8b-7108f62b743c" />

<img width="1586" height="847" alt="image" src="https://github.com/user-attachments/assets/bf1b130b-e113-4ad5-9484-fdaa63940fce" />

<img width="1567" height="842" alt="image" src="https://github.com/user-attachments/assets/4e6a4502-fd9e-4590-a773-f8089de1e5c2" />

---

## ✨ Key Features

* **Bug-Free Logic:** Correctly handles all 10 guesses, provides feedback on the final guess, and resets the game state flawlessly.
* **Enhanced User Experience:**
    * **On-Page Messaging:** Replaces disruptive `alert()` popups with styled, contextual messages for hints, success, and errors.
    * **Input Validation:** Checks for valid numbers, range (1-100), and **duplicate guesses**.
    * **Auto-Focus:** The input field is automatically focused for a smoother gameplay flow.
* **Refactored JavaScript:**
    * Code is wrapped in a `DOMContentLoaded` listener to ensure the DOM is ready before the script runs.
    * Clear separation of concerns with functions like `initGame`, `handleGuess`, and `updateUI`.
    * Robust state management without polluting the global namespace.
* **Modern & Responsive CSS:**
    * A clean, minimalist UI that works on all screen sizes.
    * Uses CSS variables (`:root`) for an easily themable color palette.

---

## 🚀 Getting Started

No installation is needed! This project runs directly in the browser.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```

2.  **Navigate to the project folder:**
    ```bash
    cd your-repository-name
    ```

3.  **Open the HTML file:**
    Simply open the `index.html` file in your favorite web browser.

---

## 🧠 Code Structure

The JavaScript is organized into logical functions to manage the game flow and state:

* **`initGame()`**: Initializes or resets all game state variables (random number, attempts, etc.) and UI elements to their default state.
* **`handleGuess()`**: The main function triggered on submit. It validates user input, processes the guess, and checks if the game is won or over.
* **`displayMessage()`**: A helper function to show styled feedback to the user (e.g., success, warning, or danger messages).
* **`updateUI()`**: Updates dynamic parts of the UI, such as the list of previous guesses and the remaining attempts counter.
* **`endGame()`**: Disables the input fields and displays the "Start New Game" button when the game is over.

---

## 💻 Technologies Used

* **HTML5**: For the structure and content of the game.
* **CSS3**: For all styling, including:
    * Flexbox for layout.
    * CSS Variables for theming.
    * Responsive design principles.
* **JavaScript (ES6)**: For all game logic, DOM manipulation, and event handling.

---

## 📜 License

This project is licensed under the **MIT License**.
