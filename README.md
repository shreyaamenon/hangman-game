# 🎮 Hangman Game – JavaFX Edition
computer graphics project i did in college (in java)

This project is a graphical **Hangman Game** created using **JavaFX**. It features dynamic visuals, keyboard input, difficulty-based word selection, and animated feedback for win/loss outcomes.

---

## 🧩 Features

- 🔤 Letter-by-letter guessing using keyboard input  
- 🧠 Three difficulty levels: Easy, Medium, and Hard  
- 🎨 Visual hangman animations for incorrect guesses  
- 🖼️ Background and sprite support  
- 🔁 Game resets on click after win/loss  
- 📄 External word bank (`words.txt`) for easy word customization

---

## 📁 Folder Structure
HangmanGame/
├── hangmanMain.java        Main JavaFX application (UI + logic)
├── hangmanWords.java       Handles word storage, guessing logic, and password check
├── SparkyStones.ttf        Font file
├── words.txt               External word list categorized by difficulty
├── README.md               Project documentation (this file)

---

## 🚀 How to Run

### ✅ Prerequisites
- Java 11 or later
- JavaFX SDK (download from https://openjfx.io)

### 🧪 Compile & Run (Command Line)

1. Replace `/path/to/javafx-sdk` with the actual path to your JavaFX SDK.
```bash
javac --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls *.java
java --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls HangmanGame
