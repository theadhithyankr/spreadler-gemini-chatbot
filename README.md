# 🤖 Spreadler – Kotlin Chatbot Powered by Gemini AI

**Spreadler** is an intelligent Kotlin-based chatbot that uses **Google’s Gemini AI API** to deliver smart, conversational responses. Designed with modularity and performance in mind, it's ideal for integrating LLM-driven features into Kotlin applications.

---

## ✨ Features

- 🔮 Uses **Gemini AI (Generative Model from Google)** for conversation  
- 🧠 Context-aware, LLM-powered responses  
- 💬 Terminal-based chat interface (CLI)  
- 🧱 Fully modular Kotlin architecture  
- ⚡ Lightweight, fast, and extensible

---

## 🛠 Tech Stack

- **Language:** Kotlin  
- **Build Tool:** Gradle (Kotlin DSL)  
- **AI Integration:** Gemini API (Google AI)  
- **IDE:** IntelliJ / Android Studio

---

## 🔐 Setup: Gemini API

1. [Get access to Gemini API](https://ai.google.dev)  
2. Create an API Key and store it securely  
3. Add the following to a `.env` file or directly in the code:

```env
GEMINI_API_KEY=your_google_gemini_key_here
````

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/theadhithyankr/spreadler.git
cd spreadler
```

### 2. Build the project

```bash
./gradlew build
```

For Windows:

```bash
gradlew.bat build
```

### 3. Run the chatbot

```bash
./gradlew run
```

Chat away in your terminal using Gemini-powered intelligence.

---

## 📁 Project Structure

```
spreadler/
├── app/                  # Main Kotlin source files
│   ├── ChatBot.kt        # Core logic using Gemini
│   └── ...
├── gradle/               # Gradle wrapper
├── build.gradle.kts      # Build config (Kotlin DSL)
└── settings.gradle.kts
```

---

## 🧠 Future Upgrades (Planned)

* GUI using Jetpack Compose Desktop
* Android app extension
* Chat history and memory
* Voice input/output (Speech-to-Text + TTS)

---

## 📄 License

MIT License — free to use, extend, or remix.

---

## 👨‍💻 Author

Created by [@theadithyankr](https://github.com/theadhithyankr)
Powered by Google AI. Built for tomorrow’s conversations.

