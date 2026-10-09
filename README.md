<div align="center">

# 🎙️ Smart Voice Assistant

A Python-based AI Voice Assistant that acts as your personal digital companion. It can perform various tasks including opening applications, answering general questions using Gemini AI, fetching the latest news and weather, searching the web, and much more!

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

</div>

---

## ✨ Features

- **🗣️ Natural Voice Interaction:** Communicate with your assistant using natural language.
- **🤖 Gemini AI Integration:** Get intelligent answers and conversational responses using Google's Gemini AI.
- **💻 App Launcher:** Open applications and websites simply by asking.
- **🛠️ Custom Commands:** Teach the assistant new commands on the fly! Save personalized triggers and actions.
- **📰 Live Updates:** Fetch the latest news headlines and real-time weather information.
- **⌨️ Auto-Typing:** Dictate text and have the assistant type it out for you.

## 🎥 Demo

*(Add a demo GIF or image here)*  
`![Smart Voice Assistant](assets/videos/demog.gif)`

---

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Kaivalya221/Smart_voice_assistant.git
   cd Smart_voice_assistant
   ```

2. **Install required dependencies:**
   Make sure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **API Keys configuration:**
   Ensure you have set up your API keys (like Gemini AI or Weather API) inside the respective scripts (`gemini_ai.py`, `weather.py`, etc.).

4. **Run the assistant:**
   ```bash
   python gui.py
   # OR
   python main.py
   ```

---

## 🎯 Usage / Voice Commands

Here are a few built-in commands to get you started:

- **"open youtube"** - Opens YouTube in your default browser.
- **"open notepad"** - Opens the Notepad application.
- **"news"** - Reads out the latest top news headlines.
- **"weather"** - Tells you the current weather.
- **"type [your text]"** - Automatically types the specified text.
- **"add a custom command"** - Initiates the process to save a new personalized voice command.
- **"exit" / "quit"** - Closes the assistant.
- **Ask anything else!** Unrecognized commands will be passed to **Gemini AI** for an intelligent response.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to check [issues page](https://github.com/Kaivalya221/Smart_voice_assistant/issues) if you want to contribute.

## 📝 License

This project is licensed under the MIT License.
