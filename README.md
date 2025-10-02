# 📘 Student Tablet AI Chatbot

This is a simple **React + TypeScript** project simulating a student learning tablet with:
- 📖 **Content Viewer**: Switch between Math, Science, and English topics
- 🤖 **AI Chatbot**: A simulated chatbot (can be extended with IBM Watson / OpenAI API)

---

## 🚀 Features
- View and switch between chapters
- Ask questions to an AI chatbot (currently simulated with dummy responses)
- Easy to extend with real AI APIs

---

## 🛠️ Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/your-username/stu_tablet_ai_chatbot.git
cd stu_tablet_ai_chatbot

### 2. Install Dependencies
npm install

### 3. Run Locally
npm start

This will start the app at http://localhost:3000

### 4. Build for Production
npm run build

---

## 📂 Project Structure

stu_tablet_ai_chatbot/
├── public/          # Static assets
│   └── index.html
├── src/
│   ├── index.tsx    # Entry point
│   ├── pages/
│   │   └── Home.tsx
│   └── components/  # Reusable UI components
│       ├── ContentViewer.tsx
│       └── Chatbot.tsx
├── package.json
├── tsconfig.json
└── README.md


👨‍💻 Made with ❤️ using React & TypeScript
