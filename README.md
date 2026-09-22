# 📅 Event Countdown App

An Android app that helps you track and manage your upcoming events with a built-in countdown — built with **Kotlin** and **Room Database** as part of the DEPI program.

---

## 📱 Features

- ➕ **Add Events** — Create events with a title, date, time, and description
- ⭐ **Mark as Important** — Pin important events for quick access
- 🏠 **Home Screen** — View important events in a horizontal scroll and all upcoming events in a vertical list
- 💾 **Local Storage** — All events are saved locally using Room Database, no internet required
- 🌙 **Dark Mode Support** — Fully supports light and dark themes

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Kotlin |
| UI | XML Layouts + Material Design 3 |
| Navigation | Bottom Navigation + Fragments |
| Database | Room (SQLite) |
| Async | Kotlin Coroutines |
| Architecture | Single Activity + Multi-Fragment |
| Build | Gradle KTS |

---

## 📂 Project Structure

```
app/
├── MainActivity.kt           # Entry point, handles bottom navigation
├── HomeFragment.kt           # Displays important & upcoming events
├── AddEventFragment.kt       # Form to add new events
├── ImportantEventsFragment.kt # Displays starred events only
├── EventModel.kt             # Room entity (data model)
├── DAO.kt                    # Database queries
├── EventDatabase.kt          # Room database setup
└── EventAdapter.kt           # RecyclerView adapter
```

---

## 🚀 Getting Started

### Prerequisites
- Android Studio Hedgehog or later
- Android SDK 27+
- Kotlin 2.1.0+

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/DEPI_Event_CountDown.git
   ```

2. **Open in Android Studio**
   - File → Open → Select the project folder

3. **Run the app**
   - Connect a device or start an emulator
   - Hit the ▶️ Run button (or `Shift + F10`)

> Minimum Android version: **API 27 (Android 8.1)**

---

## 📦 Dependencies

```toml
# Room Database
androidx.room:room-runtime:2.7.0
androidx.room:room-ktx:2.7.0

# Material Design
com.google.android.material:material:1.11.0

# Lifecycle & Coroutines
androidx.lifecycle:lifecycle-runtime-ktx:2.8.7

# CardView & RecyclerView
androidx.cardview:cardview:1.0.0
```

---

## 🔮 Future Improvements

- [ ] Event notifications & reminders
- [ ] Countdown timer displayed on each event card
- [ ] Delete & edit existing events
- [ ] Search & filter events
- [ ] Cloud sync / backup

---

## 👤 Author

**Akram Muhammad Ali**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akram-el-metwally-04896333a)

---

## 🏫 About DEPI

This project was built as part of the **Digital Egypt Pioneers Initiative (DEPI)** — a national program developing Egypt's digital talent.
