# 🌤️ Weather App (Node.js + Express + EJS)

This is a simple weather app built with **Node.js**, **Express**, and the **OpenWeatherMap API**.  
Users can enter a city name and get the current temperature and weather conditions.

---

## 🚀 How to Build This Project

1. Clone or create a new project
```bas
mkdir weather-app
cd weather-app
```
2. Initialize Node.js
```bash
npm init -y
```
3. Install dependencies
```bash

npm install express body-parser ejs request
```
4. Project structure
```

weather-app/
├── server.js        # main server file
├── package.json     # npm config
├── views/           # EJS templates
│   └── index.ejs
├── public/          # static files (CSS, images, etc.)
│   └── css/style.css
```
5. Get an API Key
Sign up at OpenWeatherMap

Copy your free API key

Add it into your server.js

6. Run the app
```bash
node server.js
or
```
```bash
npm start
```

7. Open in browser
arduino
http://localhost:3000

# 📦 Dependencies
express
body-parser
ejs
request

# 🔑 API Key
You must add your own OpenWeatherMap API key. Without it, the app won’t fetch weather data.

# 📸 Example Output
makefile

London: 15°C, scattered clouds

# 📝 License
Open source under the MIT License.


---

