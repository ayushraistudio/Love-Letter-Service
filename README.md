# 💌 AR Love Letters – Personalized Letter Generator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)](https://143-letter.netlify.app)

A secure, interactive, and beautifully designed web application that allows authenticated users to generate personalized, heartfelt love letters instantly. Now featuring **5 unique design themes** and a smart sharing system that preserves your selected style.

🌐 **Live Demo:** [https://143-letter.netlify.app](https://143-letter.netlify.app)

---

## ✨ Key Features

### 🎨 Multi-Theme Design System
* **5 Unique Styles:** Choose from **Classic Love** (Pink), **Midnight Romance** (Dark/Gold), **Blue Sky** (Calm), **Vintage** (Old Paper), and **Neon Cyberpunk** (Glowing).
* **Dynamic Styling:** The entire application (Background, Fonts, Borders) adapts instantly based on the selected theme.

### 🔐 Advanced Authentication & Security
* **Secure Login/Signup:** Powered by Firebase Authentication.
* **Password Recovery:** Integrated "Forgot Password" functionality for account recovery.
* **Strict Creator Mode:** Direct URL access is blocked for creating letters without login.
* **Public Viewer Mode:** Shared links can be viewed by anyone without logging in.

### 🚀 Smart Sharing & Downloading
* **Theme-Aware Sharing:** When you share a link, the recipient sees the **exact design** you chose (fonts, colors, and theme).
* **High-Quality Download:** Download your letter as an image (`.png`) that captures the specific background and style of your chosen theme.
* **Privacy-Focused:** No personal letter data is permanently stored on a database; data is encoded securely within the shareable link.

---

## 📸 Screenshots

A glimpse into the application interface and workflow.

| **Modern Landing Page** | **User Dashboard & Input** |
| :---: | :---: |
| <img src="./assets/landing.jpg" alt="Landing Page" width="400"/> | <img src="./assets/dashboard.jpg" alt="Dashboard" width="400"/> |
| *Elegant homepage with design selection.* | *Secure area to input details.* |

| **Recipient Details Form** | **Final Generated Letter** |
| :---: | :---: |
| <img src="./assets/details-form.jpg" alt="Recipient Form" width="400"/> | <img src="./assets/final-letter.jpg" alt="Generated Letter" width="400"/> |
| *Easy-to-use input fields.* | *The beautiful final output.* |

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Advanced CSS Variables for Theming), Vanilla JavaScript.
* **Authentication:** Google Firebase Auth (Login, Signup, Reset Password).
* **Libraries:** * `html2canvas` (For generating downloadable images).
    * `FontAwesome` (For icons).
* **Fonts:** Google Fonts (Great Vibes, Playfair Display, Poppins, Cinzel, Orbitron).
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
    * Go to Project Settings and copy your Firebase Web App configuration objects.

3.  **Configure the App**
    * Locate your Firebase initialization file (e.g., inside `login.js` and `signup.html`).
    * Replace the placeholder config with your actual Firebase project keys.

    ```javascript
    // Example config structure
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

