# Tutorial 15: Event Handling in Java Swing

This repository contains Java Swing applications for **Tutorial 15** of the Object-Oriented Programming (OOP) course. The focus of this tutorial is event-driven programming using Swing components and `ActionListener`.

---

## 📌 Project Overview

| Details | Description |
| :--- | :--- |
| **Course Name** | Object Oriented Programming |
| **Course Code** | 24SJPBCST304 |
| **Academic Year** | 2026-2027 |
| **Topic** | Event Handling & Swing Controls |
| **IDE** | Eclipse Java IDE |

---

## 📝 Questions & Program Descriptions

### Question 1: Number Guessing Game
* **Goal:** Implement an interactive number guessing game that picks a random number between 1 and 100.
* **Key Features:**
  * Validates user inputs (ensures values are integers within $1$–$100$).
  * Displays real-time feedback ("Too high!", "Too low!", or "Correct!").
  * Shows the generated random number alongside the feedback message.
* **Swing Components:** `JTextField`, `JButton`, `JLabel`, `JOptionPane`.

---

### Question 2: Up / Down / Reset Counter
* **Goal:** Create a counter application with increment, decrement, and reset functionality.
* **Key Features:**
  * Initializes text field value to `0`.
  * Increments counter on clicking **Count Up**.
  * Decrements counter on clicking **Count Down**.
  * Resets counter to `0` on clicking **Reset**.
* **Swing Components:** `JLabel`, `JTextField` (read-only), `JButton` (3 controls).

---

## 🚀 How to Run in Eclipse

1. **Open Eclipse** and select your workspace.
2. Create a new Java Project:
   * **File** ➔ **New** ➔ **Java Project**
   * Project Name: `Tutorial15`
3. Add source files:
   * Right-click `src` ➔ **New** ➔ **Class**.
   * Create `Question1.java` and paste the code for Question 1.
   * Create `Question2.java` and paste the code for Question 2.
4. **Run the Programs**:
   * Open either file and press `Ctrl + F11` (or click the green **Run** button).
   * Interact with the graphical user interface.
