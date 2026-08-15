# 💌 AR Love Letters – Advanced Personalized Letter Generator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Netlify Status](https://img.shields.io/badge/Netlify-Deployed-00C7B7?style=flat-square&logo=netlify&logoColor=white)](https://love-letter-service.netlify.app)
[![Firebase](https://img.shields.io/badge/Firebase-Integrated-FFCA28?style=flat-square&logo=firebase&logoColor=black)](#)

A secure, interactive, and beautifully designed web application that allows users to generate personalized, heartfelt love letters instantly — **completely free to use**. Powered by a dual-architecture system, it features 5 handcrafted standard themes and an advanced **AI Magic Canvas** that leverages LLM technology to automatically write and style emotional letters based on minimal user input.

[![Live Demo](https://img.shields.io/badge/Live-Demo-green)](https://love-letter-service.netlify.app)

---

## ✨ Key Features

### 🎨 The Standard Creator (Stateless & Unlimited)
* **5 Unique Visual Styles:** Choose from Classic Love (Pink), Midnight Romance (Dark/Gold), Blue Sky (Calm), Vintage (Old Paper), and Neon Cyberpunk (Glowing).
* **Dynamic Styling:** The entire application (Background, Fonts, Borders) adapts instantly based on the selected theme.
* **Custom Message Support:** Users can write and personalize their own love letter messages effortlessly.

### 💎 Premium Vault (Encrypted 3D Letter Experience)

* **Three Premium Designs:** Choose from three exclusive visual experiences — **Gold, Diamond, and Rose**.
* **Immersive 3D Backgrounds:** Each Premium Vault design features an animated 3D background for a cinematic and interactive letter experience.
* **Premium Animations:** Smooth cinematic animations and visual effects create a more immersive presentation.
* **End-to-End Encrypted Letters:** Premium Vault letter content is protected using encryption before being stored.
* **Key-Protected Access:** A unique encryption key is required to open and decrypt the Premium Vault letter.
* **Encrypted Storage:** Letter content is stored in encrypted form rather than as directly readable plaintext data.
* **Personalized Background Music:** Premium Vault supports personalized background music for a more immersive experience.
* **Secure Cloud Storage:** Premium Vault projects are securely associated with the authenticated user's account.
* **30-Day Expiry:** Premium Vault letters are automatically configured to expire after 30 days.
* **Private Premium Experience:** Premium Vault requires user authentication.

### 🤖 AI Magic Letters (For Registered Users)
* **LLM-Powered Creation:** Users provide contextual inputs (relationship type, occasion, tone, custom memories), and the AI weaves a deeply personal and grammatically perfect narrative.
* **Multi-Language Support:** Generate letters in dozens of global and regional languages.
* **Auto-Generated Aesthetics:** The system automatically crafts a dynamic color palette and typography that perfectly matches the emotional vibe of the generated text.

### 🖌️ Custom Canvas (The Ultimate Personalized Experience)
* **Design It Your Way:** Exclusively for registered users, take full control over your romantic masterpiece. Customize header branding, colors, typography, text alignment, and create custom background gradients.
* **Immersive Experience:** Add beautiful background music (Romantic Piano, Lofi Chill, etc.) and select dynamic reveal animations (Fade, Slide-up, Typewriter) to make your letter truly magical.
* **Advanced Export:** Enjoy high-definition image downloads that perfectly capture your custom design, shadows, and bold text.

 ### 🎬 Animated Scrapbook (Cinematic Story Experience)

* **Turn Memories into a Story:** Create a beautiful animated scrapbook by uploading up to **4 personal photos** and writing a heartfelt message.
* **Cinematic Photo Sequence:** Photos are displayed one by one with smooth transitions, creating an emotional storytelling experience.
* **Elegant Glassmorphism Letter Box:** After the photo sequence finishes, a modern transparent glass-style message box gracefully appears with your personalized love letter.
* **Romantic Background Music:** Enhance the experience with optional background music for a cinematic feel.
* **Cloud-Saved Projects:** Authenticated users can securely save, revisit, and manage their animated scrapbooks from their personal dashboard.
* **Shareable Experience:** Every scrapbook generates a unique shareable link, allowing recipients to enjoy the complete animated presentation exactly as designed.


### 🔐 Dual-Mode Security & Data Architecture
* **Zero-Storage Guest Mode:** Letters created without logging in are compressed and encrypted directly into the URL payload (`?data=`). **No private text is stored on our servers**, ensuring ultimate privacy.
* **Stateful Cloud Dashboard:** Authenticated users enjoy a secure personal dashboard where their letters (`?id=`) are safely hosted via Google Cloud Firestore, allowing them to manage, revisit, or permanently delete their history.
* **Centralized Support & Security:** Integrated rate-limiting (Anti-Spam) to protect the ecosystem, along with a dedicated Support & Abuse ticketing system for registered users to securely manage their requests.

### 🚀 Smart Sharing & Downloading
* **Theme-Aware Sharing:** When you share a link, the recipient experiences the exact design you crafted (fonts, colors, and theme).
* **Premium Image Export:** Logged-in users and their recipients can download the letter as a high-quality `.png` image that perfectly captures the specific background and style.

---

## 📸 Screenshots

A glimpse into the application interface and workflow.

| **Modern Landing Page** | **User Input** |
| :---: | :---: |
| <img src="./assets/landing.jpg" alt="Landing Page" width="400"/> | <img src="./assets/_dashboard.png" alt="Dashboard" width="400"/> |
| *Elegant homepage * | *Design selection.* |

| **Recipient Details Form** | **Final Generated Letter** |
| :---: | :---: |
| <img src="./assets/image.png" alt="Recipient Form" width="400"/> | <img src="./assets/Letter.jpg" alt="Generated Letter" width="400"/> |
| *Easy-to-use input fields with AI options.* | *Beautiful, shareable final output.* |

| **Custom Canvas (Advanced Editor)** |
| :---: |
| <img src="./assets/custom-preview.jpg" alt="Custom Canvas" width="850"/> |
| *Complete control over typography, colors, background, music, and reveal animations.* |

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Advanced CSS Variables), Vanilla JavaScript (ES6 Modules).
* **Backend / Serverless:** Netlify Functions (Node.js).
* **Database & Auth:** Google Firebase (Authentication, Cloud Firestore).
* **AI Integration:**  Proprietary LLM-based generation system
* **Libraries:**
- `html2canvas` – generating downloadable images
- `lz-string` – URL payload compression
- `FontAwesome` – UI icons
* **Hosting:** Netlify.

## 🚀 Getting Started Locally

This repository contains the **Public Landing Page and Legal Documentation** of the AR Love Letters ecosystem. 

*Note: The core AI engine, Firebase authentication, serverless functions, and user dashboards are maintained in a separate, closed-source private repository to ensure maximum security and protect proprietary logic.*

To run this landing page locally:

1. **Clone the repository**
   ```bash
   git clone [https://github.com/ayushraistudio/Love-Letter-Service.git](https://github.com/ayushraistudio/Love-Letter-Service.git)
   cd Love-Letter-Service

2. **Run Locally**
   * No complex setup, `.env` files, or build tools are required for this frontend repo.
   * Simply open `index.html` in any modern web browser or use a VS Code extension like **Live Server**.

---

## 📄 License

Distributed under the MIT License. See the `LICENSE` file for more information.

---

## 👤 Author

**Ayush Rai**

* LinkedIn: [@ayushraistudio](https://in.linkedin.com/in/ayushraistudio)
* GitHub: [@ayushraistudio](https://github.com/ayushraistudio)

---
*Made with ❤️ and code.*
