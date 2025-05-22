# WeatherWise

**WeatherWise** is a modular Python application that provides weather insights through both interactive menus and natural language questions. It fetches real-time weather data from the OpenWeatherMap API, displays current conditions and forecast trends, and supports intelligent dialogue to help users decide on weather-related actions—like whether to carry an umbrella or wear a coat.

# WeatherWise

## 🌦️ Features

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

# WeatherWise

## 🔧 Setup Instructions

1. **Install Dependencies**

Run the following in your Python environment:

```bash
pip install pyinputplus matplotlib requests
```

# WeatherWise

2. **Configure API Key**

Open the `config.py` file and replace the placeholder with your actual OpenWeatherMap API key:

```python
API_KEY = "your_actual_api_key"
```

# WeatherWise

3. **Run the Application**

Make sure you're in the project root directory, then launch the app with:

```bash
python main.py
```

# WeatherWise

This will open a menu interface where you can:
- Check current weather
- View forecast charts
- Ask weather-related questions via natural language



