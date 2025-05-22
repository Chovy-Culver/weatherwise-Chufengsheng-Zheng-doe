# WeatherWise

**WeatherWise** is a modular Python application that provides weather insights through both interactive menus and natural language questions. It fetches real-time weather data from the OpenWeatherMap API, displays current conditions and forecast trends, and supports intelligent dialogue to help users decide on weather-related actions—like whether to carry an umbrella or wear a coat.

## Features

- Fetches real-time weather and 5-day forecasts for any city
- Visualizes:
  - Temperature trends
  - Precipitation probability
  - Wind speed
- Accepts natural language questions such as:
  - “Do I need a coat tomorrow?”
  - “Will it be windy later?”
- Uses fuzzy keyword matching to handle misspellings
- Suggests smart clothing advice based on temperature analysis

##  Setup Instructions

1.**Install Denpendencies**

Run the following in your Python environment:

```bash
pip install pyinputplus matplotlib requests
2. **Configure API Key**

Open config.py and replace the placeholder with your OpenWeatherMap API key:

python

API_KEY = "your_actual_api_key"

3.**Run the Application**

From the root directory, run:

bash
python main.py
This will launch a menu where you can:

Check current weather

View forecast charts

Ask weather-related questions


