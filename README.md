# Java CLI Trivia Game

A feature-rich, object-oriented command-line trivia game built in Java. It connects to a live REST API to generate dynamic quizzes across dozens of categories and difficulties, and features multiple game modes and a persistent local leaderboard.

## Features

* **Dynamic Questions:** Integrates with the [Open Trivia Database (OpenTDB) API](https://opentdb.com/) to fetch thousands of unique questions.
* **Customizable Quizzes:** Users can select the number of questions, difficulty (Easy, Medium, Hard), and choose from 24 different categories (e.g., Science, History, Video Games).
* **Multiple Game Modes:**
  * **Standard Quiz:** Answer questions and get immediate feedback.
  * **Timed Quiz:** A race against the clock with a custom time limit.
  * **Review Quiz:** Provides a comprehensive breakdown of all correct answers at the end of the game.
* **Persistent Leaderboard:** Saves player names and scores to a local file, sorting them dynamically by win percentage.

## Tech Stack

* **Language:** Java
* **Concepts:** Object-Oriented Programming (Inheritance, Polymorphism), File I/O, REST API Integration
* **Libraries:** `java.net.HttpURLConnection` (API requests), `org.json` (JSON parsing)

## How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/7rdamian/general-knowledge-quiz.git](https://github.com/7rdamian/general-knowledge-quiz.git)
   ```
   
2. **Dependencies:**
  Ensure you have the org.json library added to your classpath.

4. **Compile and Run:**
  Compile the source files and run the Main class located in src/main/Main.java.

## What I Learned

Building this project reinforced core Java and OOP principles. I learned how to cleanly structure a multi-class application, utilize class inheritance to easily add new game modes without repeating code, and successfully handle HTTP GET requests and JSON parsing natively in Java.


