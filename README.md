🌦️ Weather Dashboard App

A modern and responsive Weather Dashboard built using React + Vite.
This application fetches real-time weather data from the OpenWeather API and displays it in a clean blue-themed UI.

🚀 Features

🔍 Search weather by city name

🌡️ Live Weather Information

Temperature

Humidity

Wind Speed

Weather Condition

📊 Dashboard Sections:

Live Weather

Historic Weather (UI Section)

Marine Weather (UI Section)

🎨 Full Blue Gradient Design

📱 Responsive Layout

⚡ Fast Performance (Vite)

🛠️ Tech Stack

React.js

Vite

JavaScript (ES6+)

CSS3

OpenWeather API

📂 Project Structure
weather-app/
│
├── public/
│
├── src/
│   ├── components/
│   │   ├── SearchBar.jsx
│   │   ├── WeatherCard.jsx
│   │   └── Dashboard.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── App.css
│
├── package.json
└── README.md

🔑 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/your-username/weather-dashboard.git

2️⃣ Install Dependencies
npm install

3️⃣ Add Your OpenWeather API Key

Open:

src/App.jsx


Replace:

const API_KEY = "YOUR_OPENWEATHER_API_KEY";


With your actual API key from:
https://openweathermap.org/api

4️⃣ Run the Application
npm run dev


Open in browser:

http://localhost:5173

🌐 API Used

OpenWeather Current Weather API

OpenWeather Historical API (Optional)

OpenWeather Marine API (Optional)

📌 Future Enhancements

7-Day Forecast

Weather Icons & Animations

Dark Mode Toggle

Geolocation Detection

Deployment (Vercel / Netlify)

👨‍💻 Author

Developed by Arbaz
