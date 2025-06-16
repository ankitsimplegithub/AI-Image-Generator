# 🎨 AI Image Generator using Gemini API

An AI-powered image generator built entirely with **ReactJS**, integrating the **Google Gemini API** to generate images from text prompts.

---

## 🚀 Live Demo
🌐 Coming Soon (Deploy on Vercel / Netlify)

---

## 📌 Project Description

This project is a frontend-only web application that enables users to generate AI images using the **Google Gemini API**. Enter a descriptive text prompt (e.g., "a dragon flying over a city at night") and receive a unique AI-generated image instantly.

It's lightweight, responsive, and requires only a valid Gemini API key to function.

---

## 🛠️ Tech Stack

### ⚛️ Frontend
- React.js (Functional Components)
- JavaScript (ES6+)
- Tailwind CSS / Plain CSS
- Axios / Fetch API

### 🔗 External API
- **Google Gemini API (Generative AI)**

---

## ✅ Features

- ✨ Generate high-quality AI images from natural language prompts
- 📸 Display the generated image dynamically
- ⏱️ Loading state for better UX during image generation
- 🧹 Clear prompt and reset image button
- 🔐 Uses `.env` for securely storing Gemini API Key

---

## 📁 Folder Structure

AI-Image-Generator/
├── public/
│ └── index.html
├── src/
│ ├── components/
│ ├── App.js
│ ├── index.js
│ └── App.css
├── .env
├── package.json
└── README.md

yaml
Copy
Edit

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ankitsimplegithub/AI-Image-Generator.git
cd AI-Image-Generator
2️⃣ Install Dependencies
bash
Copy
Edit
npm install
3️⃣ Add Gemini API Key
Create a .env file in the root of the project:

ini
Copy
Edit
VITE_GEMINI_API_KEY=your_google_gemini_api_key
⚠️ Don't forget to restart the dev server after editing .env.

4️⃣ Run the App
bash
Copy
Edit
npm run dev




