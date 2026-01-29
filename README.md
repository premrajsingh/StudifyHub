# 🚀 StudifyHub - AI-Powered Student Learning Toolkit

<div align="center">

![StudifyHub Banner](dark_tech_hero_bg.png)

**🌐 Live Demo:** [premrajsingh.github.io/StudifyHub/](https://premrajsingh.github.io/StudifyHub/)

[![GitHub stars](https://img.shields.io/github/stars/premrajsingh/StudifyHub?style=social)](https://github.com/premrajsingh/StudifyHub)
[![GitHub forks](https://img.shields.io/github/forks/premrajsingh/StudifyHub?style=social)](https://github.com/premrajsingh/StudifyHub)

[Core Features](#-core-features) • [Tech Stack](#-tech-stack) • [Technical Challenges](#-technical-challenges) • [Setup](#-installation)

</div>

---

## 📖 Overview

**StudifyHub** is a production-ready AI-powered platform designed for the modern student. It integrates a **Smart Code Editor**, an **Intelligent AI Assistant**, and a **Multilingual Translator** into a single, seamless experience. Built with a focus on low-latency interactions and clean UI/UX.

---

## ✨ Core Features

### 💻 1. Smart Code Editor
*   **AI Execution**: Simulates code execution across 7+ languages (JS, Python, Java, C++, etc.) using LLMs.
*   **Syntax Highlighting**: Powered by CodeMirror for a professional IDE feel.
*   **History Persistence**: LocalStorage integration to track and reload past snippets.

![Code Editor](codeeditor.jpg)

### 🤖 2. Intelligent AI Assistant
*   **Deep Reasoning**: Leverages Llama 3.3 70B via Groq API for near-instant responses.
*   **Contextual Chat**: Maintains session history with an elegant, responsive sidebar.
*   **Persistent Sessions**: Chat history saved locally for uninterrupted learning.

![AI Assistant](ai%20assistant.jpg)

### 🌍 3. Multilingual Translator
*   **Real-time Translation**: Instant bidirectional translation across 12+ global languages.
*   **Voice Integration**: Native Web Speech API for high-quality text-to-speech.
*   **Productivity Tools**: One-click copy and quick language swapping.

![Translator](translator.png)

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3 (Vanilla), JavaScript (ES6+), Bootstrap 5.3.
- **Libraries**: CodeMirror (Editor), Font Awesome & Bootstrap Icons.
- **APIs**: Groq API (Intelligence Engine), Web Speech API (TTS), Clipboard API.
- **Storage**: LocalStorage API for client-side persistence (Zero-DB architecture).

---

## 🧠 Technical Challenges & Solutions

### Simulated Code Execution
**Challenge**: How to execute untrusted code in multiple languages without a backend?
**Solution**: Engineered a sophisticated prompt-injection strategy for the Groq API to simulate standard library behaviors and I/O operations, delivering a "serverless" execution experience.

### Zero-Latency Sidebar
**Challenge**: Creating a persistent, smooth sidebar navigation for chat history.
**Solution**: Implemented a custom CSS transition engine coupled with asynchronous DOM batching to ensure the UI remains buttery smooth even with large historical datasets.

---

## 🚀 Installation

1.  **Clone the Repo**:
    ```bash
    git clone https://github.com/premrajsingh/StudifyHub.git
    cd StudifyHub
    ```
2.  **API Configuration**:
    Add your Groq API Key to:
    *   `index01.js` (line 9)
    *   `index5.js` (line 105)
    *   `index02.js` (line 1)
3.  **Run Locally**:
    Open `index.html` in any browser or use `python3 -m http.server`.

---

## 👨‍💻 Author

**Prem Raj Singh**
[GitHub](https://github.com/premrajsingh) • [LinkedIn](https://www.linkedin.com/in/premrajsingh) • [Instagram](https://www.instagram.com/im_premrajsingh_)

---

<div align="center">
⭐ If you find this project impressive, please consider giving it a star! ⭐
</div>
