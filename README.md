# 🎮 Tic-Tac-Toe Game Engine (Core Java OOP)

[![Java 17](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![OOP](https://img.shields.io/badge/OOP-Inheritance_%26_Polymorphism-2563EB?style=for-the-badge)](https://en.wikipedia.org/wiki/Object-oriented_programming)
[![Clean Code](https://img.shields.io/badge/Clean_Code-Modular-10B981?style=for-the-badge)](https://en.wikipedia.org/wiki/Clean_Code)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

An interactive, modular **Tic-Tac-Toe console game** developed in Java, demonstrating core **Object-Oriented Programming (OOP)** principles: class inheritance, polymorphism, and automated AI opponent decision logic.

---

## 🏛️ OOP Architecture

- **Player (Abstract Base Class):** Defines contract and shared state (name, mark X/O) for participants.
- **HumanPlayer (Subclass):** Handles standard input reading and coordinate validation.
- **AIPlayer (Subclass):** Simulates intelligent automated countermoves using random empty cell selection.
- **TicTacToe (Board & Engine):** Manages board state matrix, win conditions (rows, columns, diagonals), and boundary validations.
- **LaunchGame (Entry Point):** Coordinates game loop, turn alternations, and endgame announcements.

---

## ⚡ Quick Start & Run

### Prerequisites
- JDK 8 or JDK 17+ installed

### Compile & Play
``bash
# Compile
javac LaunchGame.java

# Run
java LaunchGame
``

---

## 👨‍💻 Author

**Govind Sadhanande**  
Java Backend & Full Stack Developer | Bengaluru, India  
- **LinkedIn:** [linkedin.com/in/govind-sadhanande](https://linkedin.com/in/govind-sadhanande)  
- **GitHub:** [@Govindkalal84](https://github.com/Govindkalal84)  
- **Email:** [ntg043172@gmail.com](mailto:ntg043172@gmail.com)