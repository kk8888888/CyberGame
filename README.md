# Brain Games Offline: Definitive Edition



A sleek, self-contained, offline-first collection of 12 cognitive games designed to challenge your focus, memory, logic, and creativity. All packed into a single HTML file with a dynamic, cyberpunk-inspired "Matrix" aesthetic. No internet connection required after the first load.

### [➡️ View Live Demo](https://kk8888888.github.io/CyberGame/)
show demo of pges.

---

## ✨ Features

*   **12 Diverse Brain Games:** A curated collection targeting different cognitive skills like focus, spatial reasoning, memory, and divergent thinking.
*   **Zero Dependencies & Offline First:** Everything is bundled in a single `index.html` file. Once loaded, it runs entirely in your browser, no internet needed.
*   **Sleek Cyberpunk Aesthetic:** Features a dynamic "Matrix" animated background, glitch text effects, and a neon-glow UI for an immersive experience.
*   **Responsive Design:** The interface is designed to work smoothly on both desktop and mobile devices.
*   **Score Persistence:** Your high scores for each game are automatically saved in your browser's local storage.
*   **Modular Codebase:** Built with a clean, object-oriented structure using a `BaseGame` class, making it easy to understand, maintain, or even add new games.

---

## 🎮 The Games

The collection includes 12 unique games, each designed to test a different aspect of your cognitive abilities.

| Icon | Game Name | Cognitive Skill Tested |
| :--: | :--- | :--- |
| 🚀 | **Focus Flow 2D** | Sustained Attention & Motor Control |
| 🎨 | **Color Clash** | Response Inhibition (Stroop Effect) |
| 🎧 | **Audio-Scape Recall** | Auditory Memory & Sequencing |
| 📜 | **Mental Origami** | Spatial & Visuospatial Reasoning |
| 🔗 | **Causal Chain** | Logical & Sequential Reasoning |
| 🗺️ | **Inference Island** | Deductive Logic & Problem Solving |
| 🌊 | **Rhythm Replay** | Visual Pattern Memory (Simon-like) |
| ↔️ | **Mirror Image** | Mental Rotation & Spatial Awareness |
| 💬 | **Connotations** | Abstract & Verbal Reasoning |
| ⌨️ | **Gibberish Guru** | Phonetic Decoding & Spelling |
| ❓ | **Ambiguity Riddle** | Lateral Thinking & Language Interpretation |
| 💡 | **Unusual Uses** | Divergent Thinking & Creativity |

---

## 🚀 How to Run

Because this is a self-contained static application, there are no build steps or complex installations.

### Method 1: The Easy Way (Local)

1.  **Download the Code:** Click the green `Code` button on the GitHub repo page and select `Download ZIP`.
2.  **Extract the Files:** Unzip the downloaded file on your computer.
3.  **Open the File:** Simply double-click the `index.html` file to open it in your default web browser.

That's it! The game will run locally.

### Method 2: Host on GitHub Pages (Live Demo)

You can easily host this project for free on GitHub Pages to share it with others.

1.  **Create a Repository:** Push this `index.html` file (and this `README.md`) to a new GitHub repository.
2.  **Navigate to Settings:** In your repository, go to the `Settings` tab.
3.  **Go to Pages:** In the left sidebar, click on `Pages`.
4.  **Configure the Source:**
    *   Under `Build and deployment`, set the `Source` to **Deploy from a branch**.
    *   Set the `Branch` to `main` (or `master`) and the folder to `/ (root)`.
5.  **Save:** Click `Save`.
6.  **Done!** After a minute or two, your site will be live at the URL shown on the Pages settings screen (e.g., `https://your-username.github.io/your-repo-name/`).

---

## 🛠️ Technology Stack & Architecture

This project is intentionally kept simple and accessible.

*   **Frontend:**
    *   **HTML5:** Structures the application.
    *   **CSS3:** Handles all styling, including the responsive layout, animations, and theme. It uses CSS Variables for easy theme management.
    *   **Vanilla JavaScript (ES6):** Powers all game logic, DOM manipulation, and state management. No frameworks or external libraries are used (except for the Font Awesome CDN for icons).

*   **Architecture:**
    The JavaScript code follows a clear, object-oriented pattern:
    1.  **`mainManager`:** A central controller object that handles loading/saving history, showing the main menu, launching games, and displaying modals.
    2.  **`BaseGame` Class:** A parent class that provides a template for all games. It contains shared logic for initialization, rendering, scoring, and ending a game.
    3.  **Individual Game Classes:** Each of the 12 games is an instance of a class that extends `BaseGame`, overriding methods and adding its unique content and logic. This makes the code organized and scalable.

---

## 🤝 Contributing

Contributions are welcome! If you have an idea for a new game, a bug fix, or a UI improvement, feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-awesome-feature`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some awesome feature'`).
5.  Push to the branch (`git push origin feature/your-awesome-feature`).
6.  Open a Pull Request.

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
