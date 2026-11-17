# 🌦️ Atmos – Weather Dashboard

**A modern, responsive weather dashboard built with HTML, CSS and JavaScript.**

Atmos is a stylish weather monitoring web application that provides real-time weather information for cities around the world. It features a clean midnight-blue and golden interface, dynamic weather-based backgrounds, location-based weather detection and a 5-day weather forecast.

---

## 🌐 Live Demo

🔗 **Live Website:** [Add your deployed website link here]

📂 **GitHub Repository:** [https://github.com/mdaffanuddin36-dev/WEATHER-2.0]

---

## 📸 Screenshots


### Main Dashboard
<img width="1897" height="1078" alt="Screenshot 2026-11-18 011326" src="https://github.com/user-attachments/assets/6aa8986d-8ea9-4b5b-ace4-7519046a55cb" />

### 5-Day Forecast
<img width="1871" height="897" alt="Screenshot 2026-11-18 013944" src="https://github.com/user-attachments/assets/3a6e478b-8036-49e9-b70a-f9786c676bbe" />

---

## ✨ Features

- 🌍 **City Search:** Search and view weather conditions for different cities.
- 📍 **My Location:** Automatically detect your current location and display local weather.
- 🌡️ **Real-Time Weather:** Get current temperature and weather conditions.
- 💧 **Humidity:** View the current humidity percentage.
- 🌬️ **Wind Speed:** Check the current wind speed.
- 🌡️ **Feels-Like Temperature:** View the apparent temperature.
- ◉ **Atmospheric Pressure:** Get atmospheric pressure measurements.
- 📅 **5-Day Forecast:** Check upcoming weather conditions and temperatures.
- 🎨 **Dynamic Backgrounds:** Background gradients change according to weather conditions.
- 📱 **Responsive Design:** Optimized for desktop, tablet and mobile devices.
- ⚡ **Loading & Error Handling:** Displays loading indicators and helpful error messages.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling, gradients, animations and responsive layout |
| JavaScript | Dynamic functionality and API integration |
| OpenWeatherMap API | Real-time weather and forecast data |
| Geolocation API | Detecting the user's current location |

---

## 🎨 UI Design

Atmos uses a modern dark-themed interface with a midnight-blue background and subtle golden accents.

**Design Highlights:**
- Elegant typography and rounded components.
- Glass-style weather information cards.
- Smooth hover effects and transitions.
- Responsive grid layouts.
- Weather-condition-based background gradients.

---

## ⚙️ Installation & Setup

Follow these steps to run Atmos on your local machine.

**1. Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

**2. Navigate to the project folder**

```bash
cd atmos-weather-dashboard
```

**3. Configure your OpenWeatherMap API key**

- Create an account at [OpenWeatherMap](https://openweathermap.org/).
- Generate your API key.
- Add your API key in the JavaScript configuration.

```javascript
const apiKey = 'YOUR_API_KEY';
```

**Important:** Never upload your actual API key to a public GitHub repository. For a public deployment, use a backend or another secure configuration method to protect it.

**4. Run the application**

Open the project folder in VS Code and launch `index.html` using the Live Server extension.

Alternatively, open the HTML file directly in your browser for basic testing. Location access generally requires localhost or HTTPS.

---

## 🌤️ API Integration

Atmos uses the OpenWeatherMap API to retrieve weather information.

**Current Weather API**
```text
https://api.openweathermap.org/data/2.5/weather
```

**5-Day Forecast API**
```text
https://api.openweathermap.org/data/2.5/forecast
```

Weather information is displayed dynamically using JavaScript's Fetch API.

---

## 📂 Project Structure

```text
Atmos-Weather-Dashboard/
│
├── index.html
│
├── screenshots/
│   ├── dashboard.png
│   ├── weather-details.png
│   └── forecast.png
│
└── README.md
```

*The current implementation contains HTML, CSS and JavaScript together in a single HTML file.*

---

## 🎯 Learning Outcomes

This project helped me practice and improve my understanding of:

- JavaScript DOM manipulation.
- Fetch API and asynchronous JavaScript.
- Working with external APIs.
- Async/Await and error handling.
- Browser Geolocation API.
- CSS Grid and Flexbox.
- Responsive web design.
- Dynamic UI updates.

---

## 👨‍💻 Author

**Affan Nawab**

A Computer Science student exploring web development and building projects to improve practical programming skills.

---

## ⭐ Show Your Support

If you like this project, consider giving the repository a ⭐ on GitHub!

**Built with ❤️ using HTML, CSS and JavaScript.**
