# 🧮 Modern Glassmorphism Calculator

A fully functional calculator capable of performing basic operations (addition, subtraction, multiplication, division). Features a clean user interface, keyboard support, and error handling for edge cases like dividing by zero.

## ✨ Features
* **Modern UI**: Designed with a "Glassmorphism" aesthetic using `backdrop-filter: blur(20px)` and animated background circles.
* **Calculations**: Powered by a JavaScript `Calculator` class that manages `previous-operand` and `current-operand` states.
* **Keyboard Support**: Full support for number keys, operators, `Enter` for equals, and `Backspace` for deleting.
* **Precision**: Handles decimal numbers and limits floating-point issues using `toFixed(10)`.
* **Error Handling**: Displays "Div by 0" when attempting to divide by zero.

## 🤖 AI Refactoring
This project was initially developed by me and subsequently refactored with the assistance of AI. The AI helped optimize the code structure by:
* Implementing the **Object-Oriented (Class)** structure for better logic management.
* Adding robust **keyboard event listeners** for a smoother user experience.
* Refining the **Glassmorphism CSS** to ensure modern styling and responsiveness.

## 🛠️ Built With
* **HTML5**: Semantic structure using custom `data-attributes`.
* **CSS3**: Custom properties (variables), Flexbox, Grid, and Keyframe animations.
* **JavaScript**: Object-Oriented Programming (OOP) and DOM event listeners.

## 📜 License
This project is licensed under the **MIT License**.
