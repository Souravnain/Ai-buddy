# 🎓 AI Study Buddy

**AI Study Buddy** is a premium, AI-powered study assistant designed to help students master subjects through personalized chat, dynamic explanations, and interactive quizzes.

## ✨ Features

- **Personalized Onboarding**: Tailors the AI's personality to your subject and goals.
- **Glassmorphism UI**: Beautiful, modern dashboard with a dark-mode-first aesthetic.
- **Interactive Quizzes**: Generate context-aware 5-question tests to verify your knowledge.
- **Progress Tracking**: Real-time accuracy monitoring and weak topic visualization.
- **Mock Mode**: Functional demonstration mode that works even without an API key!

---

## 🚀 Getting Started

Follow these steps to get the project running on your local machine:

### 1. Prerequisites
Ensure you have [Node.js](https://nodejs.org/) installed on your system.

### 2. Setup Environment Variables
The app requires an OpenAI API key for live AI features.
- Locate the `.env` file in the root directory.
- Add your API key:
  ```env
  VITE_OPENAI_API_KEY=your_actual_key_here
  ```
- *Note: If you leave it as 'your_key_here', the app will run in **Mock Mode** for demonstration.*

### 3. Install Dependencies
Open your terminal in the project folder and run:
```bash
npm install
```

### 4. Run the Development Server
Start the app by running:
```bash
npm run dev
```

### 5. Open the App
The terminal will provide a local URL (e.g., `http://localhost:5173/`). Open this link in your browser to start studying!

---

## 🛠️ Built With

- **React** - Frontend framework
- **Vite** - Lightning-fast build tool
- **Plain CSS** - Custom premium styling (Glassmorphism)
- **OpenAI API** - AI intelligence engine
