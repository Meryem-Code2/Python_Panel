📊 Terminal Dashboard – Weather & Banking Overview

A Python-based terminal dashboard built with Rich, combining real-time weather forecasts and bank transaction summaries in a single, stylish interface.

The application features a theme system with live previews, location-based weather data using external APIs, and automatic parsing of local bank CSV statements to calculate expenses, income, and account balance — all rendered in a structured, readable terminal layout.

✨ Features

🌦 Hourly & weekly weather forecast by city name

🗺 Automatic geolocation using Geoapify

🎨 Multiple terminal themes with live preview (Classic, Midnight, Forest, Sunset, High Contrast)

💰 Banking overview from CSV files

Total spent

Total received

Current balance

📋 Transaction table rendered with Rich

📦 Modular and extensible code structure

🖥 Optimized for readability in the terminal

🛠 Technologies Used

Python 3

Rich (layout, tables, themes)

OpenWeather API

Geoapify API

Requests

PyFiglet

📂 Folder Structure

02_Bankauszüge/ – Bank CSV statements (auto-loaded latest file)

requirements/ – API key management

Main dashboard script – handles UI, weather, and banking logic

🚀 Usage

Insert your API keys for Geoapify and OpenWeather

Place your bank CSV files into 02_Bankauszüge/

Run the script

Choose a theme and enter a city name
