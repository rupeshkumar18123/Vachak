# 🎙️ Vachak - A Voice Assistant for Visually Impaired Users

> Empowering the visually impaired with voice-first mobile interaction.

---

## 📱 About the Project

**Vachak** is an Android-based voice assistant app developed to help visually impaired individuals interact with their smartphones hands-free. It allows users to set alarms, make calls, get weather updates, toggle the flashlight, and more — all through intuitive voice commands. By minimizing the need for visual interaction, Vachak aims to promote digital inclusion and independence.

---

## 🚀 Features

- 🎤 **Voice Recognition** using Android's `SpeechRecognizer`
- 🌦️ **Real-Time Weather Updates** using OpenWeatherMap API
- ⏰ **Alarm Setup** with voice input
- 📞 **Call Helper** for contact-based calling
- 🔦 **Flashlight Control**
- 🔊 **Text-to-Speech** feedback for all responses
- 📲 **App Launcher** to open apps with voice commands
- 🔔 **Notification Reader** (reads incoming messages and alerts)
- 🧠 **NLP Intent Matcher** for natural command understanding
- 🎛️ **Modular and Extensible Design**

---

## 🛠️ Tech Stack

- **Language:** Java
- **Platform:** Android (API 21+)
- **Speech Recognition:** Android `SpeechRecognizer`
- **TTS:** Android `TextToSpeech`
- **APIs:** OpenWeatherMap API

---

## 🧩 Architecture Overview

- `MainActivity.java`: Core voice listening loop and command handler
- `SpeechListener.java`: Handles wake word and real-time speech recognition
- `WeatherHelper.java`, `CallHelper.java`, `FlashlightHelper.java`: Functional modules
- `NLPIntentMatcher.java`: Maps speech to intents using simple rule-based logic

---

## 📦 Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/vachak-voice-assistant.git
   ```

2. Open in **Android Studio**.

3. Add your **OpenWeatherMap API key** in `WeatherHelper.java`.

4. Build & Run the project on a real Android device.

---

## 📄 Prior Art & References

- Google Voice Access
- Android TalkBack

---

## 🤝 Contributors

- **Rupesh Kumar**

---

## 📜 License

This project is for educational and research purposes. Feel free to fork and build upon it with credit.

---
