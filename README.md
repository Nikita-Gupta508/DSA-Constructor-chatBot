# 🤖 DSA Instructor Chatbot

An interactive AI-powered chatbot designed to help students master **Data Structures and Algorithms (DSA)** through conversation. Built with **React**, **TypeScript**, and **Tailwind CSS**, this app leverages **Google's Gemini API** to generate educational explanations, hints, and code samples.

🌐 **[Live Demo](https://dsa-instructor-chatbot-ccjg-abhi17bgps-projects.vercel.app)**

---

## ✨ Features

* 📘 **Interactive DSA Learning**: Get real-time help with DSA topics like arrays, trees, sorting, dynamic programming, and graphs.
* 💬 **Conversational UI**: Ask questions in natural language and get clear, AI-generated responses.
* 💡 **Step-by-Step Code Help**: Receive code snippets and explanations tailored to your query.
* ⚡ **Fast Development with Vite**: Ultra-fast bundling and hot reloading.
* 🎨 **Responsive Design**: Styled using modern utility classes with Tailwind CSS.
* 🔁 **Typing and Loading Feedback**: Live chatbot UI includes visual indicators for typing and loading states.
* 🌙 **Dark Mode Friendly**: Looks great in both light and dark themes.

---

## 🧱 Tech Stack

| Tech         | Purpose                                    |
| ------------ | ------------------------------------------ |
| React + Vite | Frontend framework + blazing-fast tooling  |
| TypeScript   | Strong typing and developer productivity   |
| Tailwind CSS | Utility-first CSS styling                  |
| Zustand      | Lightweight and intuitive state management |
| Gemini API   | AI backend for intelligent chat replies    |

---

## 📁 Project Structure

```
dsa-instructor-chatbot/
├── index.html                # HTML entry point
├── package.json              # Project metadata and dependencies
├── vite.config.ts            # Vite configuration
├── tailwind.config.js        # Tailwind CSS customization
├── postcss.config.js         # PostCSS plugins
├── tsconfig*.json            # TypeScript compiler configs
└── src/
    ├── main.tsx              # React app entry point
    ├── components/           # Reusable UI components
    ├── hooks/                # Custom hooks (e.g., useChat)
    ├── services/             # API communication (Gemini handler)
    ├── types/                # TypeScript types and interfaces
    └── data/                 # Prompt templates and static data
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/abhi17bgp/dsa-instructor-chatbot.git
cd dsa-instructor-chatbot/project
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Create `.env` File

Create a `.env` file in the root of your project and add your Gemini API key:

```env
VITE_GEMINI_API_KEY=your_actual_gemini_api_key_here
```

> Note: Vite requires all environment variables to start with `VITE_`.

### 4. Run the App

```bash
npm run dev
```

Then open your browser at [http://localhost:5173](http://localhost:5173) 🚀

---

## 📚 Future Enhancements

* 📌 Add session history and chat export
* 🎤 Voice input integration
* 🌍 Multi-language support
* 🧠 Model switching: Gemini Pro, GPT-4, etc.
* 🧩 Plugin support for algorithm visualization

---

## 🙌 Credits

* Built by \[Abhi17bgp]\([https://github.com](https://github.com)
