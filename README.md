<<<<<<< HEAD

# ⏳ Java Pomodoro Timer

A sleek, distraction-free **Pomodoro-style countdown timer** built with Java Swing. Designed for deep work sessions, it launches a frameless, always-on-top window with a live countdown — ideal for maintaining focus in timed intervals.

---

## 🚀 Features

- ⏱️ **25-minute default timer** — easily customizable
- 🧼 **Minimalist UI** — frameless, always-on-top for zero distractions
- 🧠 **Clean architecture** — separates timer logic from GUI components
- 🔄 **Real-time updates** — countdown refreshes every second
- 🛠️ **Developer-friendly** — simple to tweak, extend, or integrate

---

## 📁 Project Structure

```
src/
└── org.example
    ├── Main.java
    ├── gui/
    │   └── GUI.java
    └── service/
        └── CountdownTimer.java
```

---

## ⚙️ Requirements

- Java 8 or higher
- Any Java IDE (e.g. IntelliJ, Eclipse) or terminal with `javac`

---

## ▶️ Getting Started

git clone https://github.com/AkshatSharma291106/SwingTimer.git
cd SwingTimer


```bash
cd SwingTimer
javac -d out (Get-ChildItem -Recurse -Filter *.java | ForEach-Object { $_.FullName })
java -cp out org.example.Main
```

To customize the timer duration, edit `CountdownTimer.java`:

```java
new CountdownTimer(25); // 25 = 25 minutes
```

---

## 💡 Tip

Want to experiment with different intervals (e.g. 50/10 or 90/20)? Just change the constructor argument and recompile — no extra config needed.

---

Let me know if you'd like to add screenshots, a license section, or GitHub badges for visibility.
=======
# Calculator
A very basic calculator application created using Java **Swing**. 

[![License MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Thank You!
Please ⭐️ this repo and share it with others

## Screenshots
|                Scientific / Dark                | Standard / Colored |
:------------------------------------------------:|:-------------------|
 ![Dark calculator screenshot](screenshots/scientific-dark.png) | ![Colored calculator screenshot](screenshots/standard-light.png)

## Requirements 🔧
* Java 11 or higher.

## Installation 🔌
1. Press the **Fork** button (top right the page) to save copy of this project on your account.

2. Download the repository files (project) from the download section or clone this project by typing in the bash the following command:

       git clone https://github.com/HouariZegai/Calculator.git
3. Imported it in Intellij IDEA or any other Java IDE.
4. Run the application :D

## Contributing 💡
If you want to contribute to this project and make it better with new ideas, your pull request is very welcomed.
If you find any issue just put it in the repository issue section, thank you.
>>>>>>> 396ef57 (Initial commit)
