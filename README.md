# 💌 AR Love Letters – Personalized Letter Generator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Netlify Status](https://api.netlify.com/api/v1/badges/b4217887-1337-4206-9237-YOUR-NETLIFY-ID/deploy-status)](https://app.netlify.com/sites/143-letter/deploys) A secure, interactive, and beautifully designed web application that allows authenticated users to generate personalized, heartfelt love letters instantly. Built with a focus on user privacy and a modern UI experience.

🌐 **Live Demo:** [https://143-letter.netlify.app](https://143-letter.netlify.app)

---

## ✨ Key Features

* **🔐 Secure Authentication:** Implemented Firebase Email/Password authentication. Only verified users can access the letter generation tools.
* **🛡️ Privacy-Focused:** User sessions are managed securely. No personal letter data is permanently stored on public databases.
* **⚡ Instant Generation:** Create custom letters in real-time by entering recipient details and custom messages without page reloads.
* **🎨 Modern & Responsive UI:** A clean, professional interface with elegant typography and smooth transitions.
* **🌓 Dark/Light Mode:** Built-in theme toggler for comfortable viewing in any lighting condition.

---

## 📸 Screenshots

A glimpse into the application interface and workflow.

| **Modern Landing Page** | **User Dashboard & Input** |
| :---: | :---: |
| <img src="./assets/landing.png" alt="Landing Page" width="400"/> | <img src="./assets/dashboard.png" alt="Dashboard" width="400"/> |
| *Elegant homepage with clear CTAs.* | *Secure area to input details.* |

| **Recipient Details Form** | **Final Generated Letter** |
| :---: | :---: |
| <img src="./assets/details-form.png" alt="Recipient Form" width="400"/> | <img src="./assets/final-letter.png" alt="Generated Letter" width="400"/> |
| *Easy-to-use input fields.* | *The beautiful final output.* |



---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (CSS Variables for theming), Vanilla JavaScript.
* **Authentication & Backend Services:** Google Firebase Authentication.
* **Icons & Typography:** Font Awesome, Google Fonts (Montserrat & Playfair Display).
* **Hosting:** Netlify.

---

## 🚀 Getting Started Locally

To run this project locally, you need to set up your own Firebase project.

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/ayushraistudio/Love-Letter-Service.git](https://github.com/ayushraistudio/Love-Letter-Service.git)
    cd Love-Letter-Service
    ```

2.  **Setup Firebase**
    * Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project.
    * Navigate to **Build > Authentication** and enable the **Email/Password** sign-in method.
    * Go to Project Settings and copy your Firebase Web App configuration objects (API Keys, etc.).

3.  **Configure the App**
    * Locate your Firebase initialization file (e.g., `firebase.js` or inside your main script).
    * Replace the existing placeholder config with your actual Firebase project keys.

    ```javascript
    // Example config structure within your JS file
    const firebaseConfig = {
      apiKey: "YOUR_API_KEY",
      authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
      projectId: "YOUR_PROJECT_ID",
      storageBucket: "YOUR_PROJECT_ID.appspot.com",
      messagingSenderId: "YOUR_SENDER_ID",
      appId: "YOUR_APP_ID"
    };
    ```

4.  **Run the project**
    * Simply open `index.html` in your browser (or use a live server extension).

---

## 📄 License

Distributed under the MIT License. See the `LICENSE` file for more information.

---

## 👤 Author

**Ayush Rai**

* LinkedIn: [@ayushraistudio](https://in.linkedin.com/in/ayushraistudio)
* GitHub: [@ayushraistudio](https://github.com/ayushraistudio)

---
Made with ❤️ and code.
