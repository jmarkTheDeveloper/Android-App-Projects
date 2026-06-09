# 🕊️ Sora — Personal Finance Manager (Android)

> *Sora* (空) — Japanese for "sky." Look up, take control.

Sora is a personal finance management application for Android, designed to help users track income, monitor expenses, manage budgets, and gain insight into their spending habits — all in one clean, intuitive interface.

This is the Android counterpart to the [Sora JavaFX Desktop App](https://github.com/jmarkTheDeveloper/Java/tree/main/Sora), sharing the same core concept and financial logic but rebuilt natively for mobile using Android SDK and Java.

---

## Features

- **Dashboard Overview** — At-a-glance summary of your balance, income, and expenses
- **Expense & Income Tracking** — Log transactions with category, amount, date, and notes
- **Budget Management** — Set monthly budget limits and track spending against them
- **Transaction History** — Searchable and filterable list of past transactions
- **Philippine Peso (₱) Support** — Localized for Filipino users
- **Clean, Minimal UI** — Sky-blue color palette with dove/bird branding consistent with the Sora identity

---

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Java |
| UI Framework | Android SDK (XML Layouts) |
| Architecture | MVC / Activity-based |
| Local Storage | SQLite / SharedPreferences |
| Build Tool | Gradle |

---

## Getting Started

### Prerequisites

- Android Studio (latest stable)
- Android SDK API 26+ (Android 8.0 Oreo or higher)
- JDK 11 or higher

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jmarkTheDeveloper/Android-App-Projects.git
   ```

2. Open Android Studio and select **Open an Existing Project**.

3. Navigate to `Android-App-Projects/Sora` and open it.

4. Let Gradle sync, then run on an emulator or physical device.

---

## Project Structure

```
Sora/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/         # Activity and logic classes
│   │   │   ├── res/
│   │   │   │   ├── layout/   # XML UI layouts
│   │   │   │   ├── drawable/ # Icons and assets
│   │   │   │   └── values/   # Colors, strings, themes
│   │   │   └── AndroidManifest.xml
│   └── build.gradle
└── README.md
```

---

## Related Projects

- [Sora — JavaFX Desktop](https://github.com/jmarkTheDeveloper/Java/tree/main/Sora) — The original desktop version of this application built with JavaFX and a Python ML backend for expense forecasting.

---

## Author

**Mark Almeria** — [@jmarkTheDeveloper](https://github.com/jmarkTheDeveloper)  
BS Computer Science — Digital Forensics | National University Philippines

---

## License

This project is for educational purposes as part of coursework at National University Philippines.
