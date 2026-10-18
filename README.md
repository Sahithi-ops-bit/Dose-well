# Dose-well
# 💊 DoseWell

**Never miss a dose again.** DoseWell is a medicine reminder app with a multilingual voice assistant that speaks your reminders aloud, in the language you're most comfortable with.

![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-[Android%20%7C%20iOS%20%7C%20Web]-blue)
![Status](https://img.shields.io/badge/status-active-brightgreen)

---

## 📖 About

Forgetting medicines is a common problem, especially for elderly people, patients on long-term treatment, and people who don't read well or are more comfortable in their regional language. DoseWell solves this with timely notifications and a voice assistant that reminds users out loud in their own language.

## ✨ Features

- ⏰ **Smart Medicine Reminders**: schedule one-time, daily, weekly, or custom-interval doses
- 🗣️ **Multilingual Voice Assistant**: spoken reminders in multiple languages
- 🌐 **Multi-language Interface**: the app UI adapts to the selected language
- 💊 **Medicine Management**: add, edit, and delete medicines with dosage, timing, and notes
- 🔔 **Persistent Notifications**: alerts that work even when the app is closed
- ✅ **Dose Tracking**: mark doses as taken, skipped, or snoozed
- 📅 **History & Adherence**: view your past intake records
- 🔊 **Voice Commands** *(optional)*: [e.g. "Remind me to take paracetamol at 8 PM"]
- 👴 **Accessible Design**: large text and simple navigation for elderly users

## 🌍 Supported Languages

| Language | Voice Reminders | UI |
|----------|:---------------:|:--:|
| English  | ✅ | ✅ |
| Hindi    | ✅ | ✅ |
| Telugu   | ✅ | ✅ |
| [Add more] | | |

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | [Flutter / React Native / Kotlin / Java / React] |
| Backend | [Firebase / Node.js / None (offline)] |
| Database | [SQLite / Room / Firebase Firestore] |
| Voice | [Android TextToSpeech / Google Cloud TTS / flutter_tts] |
| Notifications | [AlarmManager / flutter_local_notifications / FCM] |

## 📸 Screenshots

| Home | Add Medicine | Voice Reminder |
|------|--------------|----------------|
| ![Home](screenshots/home.png) | ![Add](screenshots/add.png) | ![Voice](screenshots/voice.png) |

## 🚀 Getting Started

### Prerequisites

- [Android Studio / VS Code / Xcode]
- [Flutter SDK 3.x / Node.js 18+ / JDK 17]
- A physical device or emulator

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/dosewell.git

# 2. Go to the project folder
cd dosewell

# 3. Install dependencies
[flutter pub get / npm install]

# 4. Run the app
[flutter run / npm start / run from Android Studio]
```

### Configuration

If you use any API keys (e.g., Firebase, Google Cloud TTS), create a config file:

```
[.env / google-services.json / config.dart]
```

> ⚠️ Never commit your API keys to GitHub.

## 📱 Usage

1. Open DoseWell and choose your preferred **language**.
2. Tap **➕ Add Medicine** and enter the name, dose, and schedule.
3. Allow **notification** and **alarm** permissions.
4. At the scheduled time, DoseWell sends a notification and the **voice assistant speaks the reminder**.
5. Mark the dose as **Taken**, **Skipped**, or **Snooze**.

## 📂 Project Structure

```
dosewell/
├── lib/ or src/          # Source code
│   ├── screens/          # UI screens
│   ├── services/         # Notification & voice services
│   ├── models/           # Data models
│   ├── localization/     # Language files
│   └── utils/
├── assets/               # Images, fonts, audio
├── screenshots/
├── README.md
└── LICENSE
```

## 🗺️ Roadmap

- [ ] Caregiver / family alerts for missed doses
- [ ] Prescription scan using OCR
- [ ] Refill and low-stock reminders
- [ ] Cloud backup and sync
- [ ] Voice-based medicine entry
- [ ] More regional languages
- [ ] Doctor appointment reminders

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push the branch: `git push origin feature/your-feature`
5. Open a Pull Request

## ⚠️ Disclaimer

DoseWell is a reminder tool only. It does **not** provide medical advice, diagnosis, or treatment. Always follow your doctor's instructions and consult a healthcare professional for medical decisions.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 👨‍💻 Author

**[Your Name]**
- GitHub: [@your-username](https://github.com/your-username)
- Email: your.email@example.com

---

⭐ If you find DoseWell useful, please give it a star!
