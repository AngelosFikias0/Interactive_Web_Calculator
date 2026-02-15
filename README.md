# Modern Web Calculator

> **A sleek, responsive web application implementing arithmetic logic, dynamic display updates, and robust error handling using vanilla JavaScript.**

This project is a functional study in building interactive user interfaces. It focuses on capturing sequential button events, managing an expression buffer, and executing mathematical operations through a clean, accessible design.

---

## 📌 Logic & Workflow

The application operates by listening for click events and updating the display in real-time, validating the expression before execution.



```text
       [ User Interaction ]
       (Button Click/Keyboard)
                  |
        /---------+---------\
        |                   |
 [ Digit/Operator ]    [ Special Keys ]
 (Append to Buffer)    (Clear / Delete)
        |                   |
        \---------+---------/
                  |
                  v
       [ Expression Parser ]
       (JS Evaluation Logic)
                  |
                  v
       [ Display Controller ]
       (UI Update / Error Output)
```

---

## 🚀 Key Features

* **Core Arithmetic:** Supports Addition (`+`), Subtraction (`-`), Multiplication (`*`), and Division (`/`).
* **Advanced Math:** Includes "Raise to Power" (`**`) functionality for exponential calculations.
* **Precision Control:** Optimized display to handle long decimal results and prevent overflow.
* **Smart Reset:**
    * **Clear (C):** Resets the entire expression buffer.
    * **Delete:** Removes only the last character entered for quick corrections.
* **Resilience:** Built-in error handling to manage invalid mathematical syntax (e.g., dividing by zero or consecutive operators).

---

## 🧰 Technical Stack

| Category | Technology |
| :--- | :--- |
| **Structure** | HTML5 (Semantic elements) |
| **Styling** | CSS3 (Flexbox/Grid for layout) |
| **Logic** | Vanilla JavaScript (ES6+) |
| **Version Control** | Git |

---

## 📊 Design Philosophy

* **Responsive UI:** The layout adapts to various viewports, ensuring the buttons remain tactile and readable on mobile, tablet, and desktop.

* **Accessibility:** High-contrast buttons and clear font choices prioritize readability.
* **Event Delegation:** Efficient event handling to manage multiple button interactions with minimal code overhead.

---

## 🛠️ Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/AngelosFikias0/Calculator_App.git](https://github.com/AngelosFikias0/Calculator_App.git)
   cd Calculator_App
   ```
2. **Launch:**
   Open `index.html` in any modern web browser to start calculating.

---

## 📈 Engineering Highlights

* **Input Sanitization:** Logic that prevents users from entering invalid character sequences.
* **Functional Programming:** Heavy use of pure functions to manage calculations, making the code modular and easy to test.
* **CSS Transitions:** Smooth visual feedback on button presses to mimic a physical hardware experience.

---

## 📄 License
This project is open-source and available under the **MIT License**.

---
**Developed by Angelos Fikias** *Mastering the foundations of interactive web logic.*
