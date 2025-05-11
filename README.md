# Weather App

A simple weather application built with React.js and Vite that allows users to search for cities and view current weather details (temperature, humidity, wind speed) along with corresponding weather icons. Data is fetched from the openweathermap API.  
➡️ Live demo: [https://binil-dangol.github.io/Weather-App/](https://binil-dangol.github.io/Weather-App/)

---

## Table of Contents

- [Features](#features)  
- [Demo](#demo)  
- [Getting Started](#getting-started)  
- [Available Scripts](#available-scripts)  
- [Project Structure](#project-structure)  
- [Technologies Used](#technologies-used)  
- [License](#license)  

---

## Features

- 🌤️ **City Search** – Enter a city name and press Enter or click the search icon.  
- 🌡️ **Current Weather** – Displays temperature, humidity, and wind speed.  
- 🌦️ **Weather Icons** – Shows an icon matching the current weather conditions.  
- 🔄 **Responsive Design** – Optimized for mobile (iPhone SE) and larger screens (Nest Hub).  
- ⚡ **Fast Dev Experience** – Powered by Vite’s lightning-fast hot module replacement.  

---

## Demo

<div align="center">
  <img src="src/assets/SS_(iPhone SE).png" alt="Weather app on iPhone SE" width="300" />
  <p><i>Figure 1: Weather app on iPhone SE</i></p>

  <img src="src/assets/SS_(Nest Hub).png" alt="Weather app on Nest Hub" width="300" />
  <p><i>Figure 2: Weather app on Nest Hub</i></p>
</div>

Check out the live demo here: [https://binil-dangol.github.io/Weather-App/](https://binil-dangol.github.io/Weather-App/)

---

## Getting Started

1. **Prerequisites:**  
   - Node.js v14+  
   - npm v6+ (or Yarn)

2. **Clone, install dependencies & start the dev server:**  
   ```bash
   git clone https://github.com/binil-dangol/Weather-App.git
   cd Weather-App
   npm install
   npm run dev

3. Open your browser at http://localhost:5173 (or the URL shown in the console).

---

## Available Scripts
In the project directory, you can run:

| Command           | Description                                     |
| ----------------- | ----------------------------------------------- |
| `npm run dev`     | Start Vite dev server (hot-reload enabled)      |
| `npm run build`   | Create a production build in the `dist/` folder |
| `npm run preview` | Preview the production build locally            |
| `npm run lint`    | Run ESLint on all `.js/.jsx` files              |

---

## Project Structure

```text
Weather-App/
├── public/
│   ├── favicon.ico
│   └── index.html
├── src/
│   ├── assets/
│   │   ├── SS_(iPhone SE).png
│   │   └── SS_(Nest Hub).png
│   ├── components/
│   │   ├── SearchBar.jsx       # Search input and icon
│   │   ├── WeatherCard.jsx     # Displays weather info & icon
│   │   └── ...other components
│   ├── App.jsx                 # Main layout & state
│   ├── main.jsx                # Entry point
│   └── index.css               # Global styles
├── .gitignore
├── package.json
├── vite.config.js
└── README.md
```

---

## Technologies Used

- React.js
- Vite
- openweathermap API
- CSS

---

## License
This project is open source and available under the MIT License.
