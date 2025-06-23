# PRODIGY_WD_05
# ☀️ Weather App

A modern and responsive Weather App built using HTML, CSS, and JavaScript (with optional API integration). The app provides real-time weather information such as temperature, humidity, and weather conditions based on the user's city or current location.

---
## 🌟 Features

- 🔍 Search weather by city name
- 📍 Get weather using current location (Geolocation API)
- 🌡️ Displays temperature, weather condition, humidity, wind speed, etc.
- 🎨 Responsive and clean UI design
- ⛅ Dynamic weather icons and background (optional)
- 🌐 Powered by OpenWeatherMap API *(or any other weather API)*

---

## 🧰 Technologies Used

- **HTML5** – Page structure
- **CSS3** – Styling and layout (Media Queries, Flexbox)
- **JavaScript (ES6)** – App logic and API integration
- **OpenWeatherMap API** – Real-time weather data

---

## 📁 Folder Structure

weather-app/
│
├── weather_app.html # Main HTML file
├── css(integrated)/
│ └── style.css(integrated) # Styling
├── js(integrated)/
│ └── script.js(integrated) # JavaScript logic and API integration
├── images/ # Optional images/icons
├── .env (optional) # API key (if using dotenv or local server)
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🖼️ Screenshots

### Desktop View
![Desktop Screenshot](screenshots/desktop.png)

### Mobile View
![Mobile Screenshot](screenshots/mobile.png)

---

## ⚙️ How to Use Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
Navigate to the project folder:

bash
Copy
Edit
cd weather-app
Open weather_app.html in your browser.
(If you're using an API key, insert it in the script file where required.)

🔑 API Setup (OpenWeatherMap)
Go to https://openweathermap.org/api

Sign up and get your free API key.

Replace "YOUR_API_KEY" in the script.js file with your actual API key:

javascript
Copy
Edit
const apiKey = "YOUR_API_KEY";
🚀 Future Enhancements
 Add 5-day weather forecast

 Show sunrise/sunset times

 Add dark/light mode toggle

 Use chart libraries for temperature graphs

🙏 Acknowledgements
Weather data provided by OpenWeatherMap

Icons from Font Awesome

Fonts from Google Fonts

📄 License
This project is licensed under the MIT License.

