
# 🌍 LnL Legends

LnL Legends is an interactive map quiz game where players try to locate real-world places based on photos. The game tests the player's geographic knowledge by calculating the accuracy of each guess using both **distance** and **response time**.

🔗 **Live demo:** [tomasulman-lnl-legends.netlify.app](https://tomasulman-lnl-legends.netlify.app/)

---

## 🎮 Gameplay

1. Select a quiz and click **Play**.
2. A photo of a place appears – mark its location on the map.
3. After submitting the guess:
   - The correct location is revealed.
   - A line is drawn between the guess and actual position.
   - Score is calculated based on distance and remaining time.
4. Continue through the questions. At the end, a final score and animated summary are displayed.

---

## 🧠 Purpose

- Practice Object-Oriented JavaScript (OOP)
- Work with interactive maps using Leaflet
- Simulate a full game flow with score tracking
- Explore UX details like modals, transitions and scoring logic

---

## 💻 Technologies Used

- JavaScript (OOP)
- HTML & CSS
- [Leaflet.js](https://leafletjs.com/) – interactive maps
- [OpenStreetMap](https://www.openstreetmap.org/copyright)
- [CartoDB](https://carto.com/attributions)
- [Pixabay](https://pixabay.com/) – image source

---

## 🚀 Run Locally

```bash
git clone https://github.com/TomasUlman/LnL_Legends.git
cd LnL_Legends
Open index.html in your browser
```

---

## 📁 Architecture Overview

- `app.js` – Main controller class handling app logic, quiz menu, user modal, and localStorage
- `quiz.js` – Quiz class managing map rendering, image display, interaction, scoring, and state transitions
- `question.js` – Encapsulates question structure (image, coordinates, location name)
- `quizData.js` – All quiz content and map settings in one place

---

## 📦 Features

- Real-time guess evaluation on the map
- Distance and time-based scoring system
- LocalStorage to remember best scores
- Dynamic quiz creation from config file
- Animated feedback and transitions
- Fully standalone (no backend)

---

© 2025 Tomáš Ulman – Personal project for learning and fun.
