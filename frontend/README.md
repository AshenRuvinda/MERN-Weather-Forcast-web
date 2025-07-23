Weather Forecast App
A responsive weather forecast web application built with the MERN stack (MongoDB, Express.js, React, Node.js) and styled with Tailwind CSS. Users can search for real-time weather data by city, including temperature, conditions, and humidity, using the OpenWeatherMap API. Optional MongoDB integration stores search history.
Project Structure
weather-forecast-app/
├── backend/
│   ├── .env
│   ├── server.js
│   ├── package.json
│   └── models/
│       └── SearchHistory.js
├── frontend/
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── components/
│   │   │   ├── SearchForm.js
│   │   │   └── WeatherCard.js
│   │   ├── pages/
│   │   │   └── Home.js
│   │   ├── App.js
│   │   ├── index.css
│   │   └── index.js
│   ├── tailwind.config.js
│   ├── postcss.config.js
│   └── package.json
├── README.md

Setup
Prerequisites

Node.js
MongoDB (optional, for search history)
OpenWeatherMap API key

Backend

Navigate to backend folder:cd backend


Install dependencies:npm install


Create a .env file with:OPENWEATHER_API_KEY=your_api_key
PORT=5000
MONGO_URI=your_mongodb_connection_string


Start the server:npm start



Frontend

Navigate to frontend folder:cd frontend


Install dependencies:npm install


Start the React app:npm start



Features

Search for weather by city using OpenWeatherMap API.
Display temperature, weather conditions, humidity, and icons.
Optional: Save and view search history with MongoDB.
Responsive design with Tailwind CSS.

Technologies

Frontend: React, Tailwind CSS, Axios
Backend: Node.js, Express.js, MongoDB (optional)
API: OpenWeatherMap

Future Enhancements

Add 5-day forecast.
Allow users to save favorite cities.
Implement loading spinners and better error handling.
