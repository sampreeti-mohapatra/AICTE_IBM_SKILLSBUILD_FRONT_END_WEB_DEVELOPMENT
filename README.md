
# 📘 Student Tablet AI Chatbot

![React](https://img.shields.io/badge/React-18-blue?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-4.0-blue?logo=typescript)
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-green)

A simple **React + TypeScript** project simulating a student learning tablet with:

* 📖 **Content Viewer**: Switch between Math, Science, and English chapters
* 🤖 **AI Chatbot**: A simulated chatbot (can be extended with IBM Watson / OpenAI API)

---

## 🚀 Features

* Browse and view subject chapters
* Chat with an AI agent (dummy responses, can be connected to real APIs)
* Simple, modular codebase for learning and extension

---

## 🖼️ Preview (Screenshot)

Here’s an example output of the app running locally:

![App Screenshot](docs/screenshot.png)

👉 *(Replace `docs/screenshot.png` with your actual screenshot after running `npm start`)*

---

## 🛠️ Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/your-username/stu_tablet_ai_chatbot.git
cd stu_tablet_ai_chatbot
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run Locally

```bash
npm start
```

The app will run at 👉 [http://localhost:3000](http://localhost:3000)

### 4. Build for Production

```bash
npm run build
```

Builds optimized files inside the `build/` folder.

---

## 📂 Project Structure

```
stu_tablet_ai_chatbot/
├── public/               # Static assets
│   └── index.html
├── src/
│   ├── index.tsx         # Entry point
│   ├── pages/
│   │   └── Home.tsx
│   └── components/       # Reusable UI components
│       ├── ContentViewer.tsx
│       └── Chatbot.tsx
├── package.json
├── tsconfig.json
└── README.md
```

---

## 📜 License

This project is licensed under the **MIT License** – you’re free to use and modify it.

---

👨‍💻 Made with ❤️ using **React + TypeScript**

