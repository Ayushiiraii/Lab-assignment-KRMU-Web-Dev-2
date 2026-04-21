# 🌦️ Weather Tracker (JavaScript DOM Project)

A simple weather tracking web app built using **Vanilla JavaScript with DOM manipulation**.  
It fetches real-time weather data and dynamically updates the UI without page reloads.

---

## 🚀 Features

- 🔍 Search weather by city name
- 🌡️ Live temperature display
- 🌥️ Weather description
- 💧 Humidity & 🌬️ wind speed
- 🕘 Dynamic search history (DOM-based buttons)
- ⚡ Instant UI updates without refresh

---

## 🧠 Core Concept: DOM Manipulation

This project focuses on **JavaScript DOM operations**:

- Selecting elements using `getElementById`
- Updating UI using `textContent`
- Creating elements dynamically (`createElement`)
- Handling user input
- Attaching event listeners
- Updating the page without reload

---

## 🛠️ Tech Stack

- HTML
- CSS
- JavaScript 
- OpenWeather API

---

## ⚙️ How It Works

1. User enters a city name
2. JavaScript captures input from the DOM
3. API call is made using `fetch()`
4. Response data is used to update DOM elements:
   - City name
   - Temperature
   - Weather
   - Humidity
   - Wind speed
5. A new button is dynamically added to search history

## 📂 Project Structure
weather-tracker/
│── index.html
│── style.css
│── script.js

## 🚧 Future Improvements
* Store history using localStorage
* Add forecast feature
* Improve UI design
* Add loading states


