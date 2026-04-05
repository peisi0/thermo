# OurChat (WeChat Web Clone)

A lightweight, single-page web application replicating the WeChat (Weixin) interface. Built entirely with **Vanilla HTML, CSS, and JavaScript**, this project demonstrates how to build a complex, mobile-responsive UI and a simulated AI chat bot without external frameworks like React or Vue.

## 🔗 Live Demo
**[View the Live Application](https://peisi0.github.io/ourchat)**

## ⚡ Key Features

### 🖥️ User Interface
* **Dark Mode Design:** Built with a native dark theme using CSS variables (`--bg-color: #111111`).
* **Mobile-First Architecture:** Optimized for touch devices with `user-scalable=no` and specific viewport handling to manage virtual keyboards.
* **Single Page Application (SPA) Feel:** Smooth tab switching and sub-page sliding animations using Vanilla JS class toggling.

### 🤖 Functional Modules
* **Integrated AI Assistant:**
    * A rule-based chatbot implemented in local JavaScript.
    * **Capabilities:** Tells jokes, remembers context (e.g., if you ask for "another" joke), and handles basic greetings.
    * **Simulation:** Mimics network latency with random timeout delays before replying.
* **Real-time Search:** A functioning search bar in the "Chats" tab that redirects queries to Google.
* **Interactive Settings:** Toggle switches and navigation menus that mimic the real app's behavior.

### 🛠️ Technical Highlights
* **Zero Dependencies:** No build tools (Webpack/Vite) or frameworks required. Just standard web technologies.
* **CSS Variables:** Easy theming via the `:root` scope.
* **Flexbox Layouts:** utilized for the complex chat bubbles and list items.

## 📂 Project Structure

The project is designed to be simple. The core logic lives in `index.html`.

```text
/
├── index.html        # Contains HTML structure, CSS styles, and JS Logic
├── manifest.json     # (Optional) For PWA installation support
├── icon.png          # (Optional) App Icon
└── README.md
