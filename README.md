# To-Do-List-Web-App
Evolve your productivity with this elegant, responsive To-Do list. Features persistent data, multiple themes, daily stats, and advanced browser API integration (Voice, Notifications).
# ✨ To-Do List Web App

A modern, visually stunning, and feature-rich To-Do List application built entirely with **Vanilla JavaScript, HTML, and CSS**. This project demonstrates advanced front-end capabilities, persistent data storage, and integration with modern browser APIs, all wrapped in a luxurious, responsive design.

## 🎨 Design & Experience

The application is crafted with a focus on elegance and user experience:

* **Design Trend:** Features a sleek **Glassmorphism** aesthetic, utilizing soft shadows, semi-transparent backgrounds, and blurred elements.
* **Color Palette:** Uses a pleasant, modern **Pastel** color scheme, customizable via a theme switcher.
* **Smoothness:** Includes numerous **CSS Transitions** for hover effects, theme changes, and component interactions, ensuring a buttery-smooth feel.
* **Responsiveness:** Fully optimized for both desktop and mobile devices.

## 🚀 Features

Beyond standard task management, To-Do offers a rich set of advanced functionalities:

### Core Management
* ✅ **CRUD Operations:** Easily Add, Edit, Delete, and Mark tasks as complete.
* 💾 **Persistent Data:** All tasks, settings, and stats are saved locally using **`localStorage`** and persist across browser refreshes.
* 🏷️ **Custom Categorization:** Tasks can be organized with custom tags (e.g., Work, Study, Personal).
* 🔄 **Drag-and-Drop Reordering:** Tasks can be reordered seamlessly using **SortableJS**.
* 🔎 **Robust Filtering:** Filter tasks by Status (All, Completed, Pending) and Category.

### Productivity & Wellness
* 🍅 **Pomodoro Focus Timer:** An integrated timer to promote focused work sessions and timed breaks.
* 🎙️ **Voice Input:** Add tasks quickly and efficiently using the **Web Speech API** for voice-to-text input.
* 🔔 **Notification Reminders:** Uses the **Notification API** to alert you when your Pomodoro session ends, even when the app is in the background.

### Stats & Gamification
* 🎯 **Daily Progress Bar:** Visualizes your completion rate for today's tasks.
* ⭐ **Gamification:** Tracks your **XP (Experience Points)** and **Completion Streak** to reward consistency.
* 📈 **Minimal Chart:** Displays task completion trends over the last 7 days using **Chart.js**.
* 🎉 **Motivational Pop-up:** Celebratory message when all active tasks are completed for the day.

### Utilities
* 🎨 **Theme Switcher:** Toggle between **Pastel**, **Dark**, and **Light** themes with smooth transitions.
* 📥 **Data Management:** Options to **Export** and **Import** all application data as a JSON file for backup or migration.
* 🧹 **App Reset:** Option to completely wipe all application data from the browser.

## 💻 Tech Stack

* **HTML5:** Semantic structure.
* **CSS3:** Styling, including Glassmorphism and animations.
* **Vanilla JavaScript (ES6+):** All application logic.

### External Libraries (CDNs)
* **SortableJS:** For drag-and-drop functionality.
* **Chart.js:** For rendering the completion statistics chart.
* **Google Fonts (Poppins):** For clean, modern typography.

## ⚙️ Installation and Setup

This is a static site and requires no complex build process or backend.

1.  **Clone the Repository (or Download):**
    ```bash
    git clone [YOUR-REPOSITORY-URL]
    cd lux-todo-app
    ```
2.  **Run Locally:**
    * Simply open the `index.html` file in your web browser.

    > **Note:** To test the Voice Input and Notification APIs, you must run the app using a local server (e.g., VS Code's Live Server extension) or deploy it, as most browsers disable these APIs on local file paths (`file://...`).

## 🌐 Deployment

This project is perfectly suited for free static hosting platforms:

* **GitHub Pages:** [Link to your live GitHub Pages site here]
* **Netlify/Vercel:** (Instructions for setting up a deployment of the root folder)

## ✍️ Contribution

Feedback, suggestions, and feature requests are welcome! If you find any bugs or have ideas for improvement, please open an issue or submit a pull request.

---

Made with ✨ by [Your Name or GitHub Handle]
