Here's a description for both versions of your weather app to use when uploading to GitHub:

---

# Weather Forecast App

This repository contains two versions of a Python-based weather application that provides current and forecast weather information. Both versions use the OpenWeatherMap API for weather data retrieval, with one version incorporating voice interaction and the other being a straightforward command-line application.

## Version 1: Voice-Interactive Weather AI

### Overview
This version of the weather app integrates voice interaction using the `pyttsx3` library for text-to-speech and `speech_recognition` for voice input. It provides current or future weather information based on user input and can alert users if certain weather conditions, such as temperature thresholds or rain, are met.

### Features
- **Voice Interaction**: Provides voice prompts and responses for user interaction.
- **Custom Alarms**: Set temperature thresholds for alerts and rain detection.
- **Current and Forecast Weather**: Retrieves and reports both current weather and 3-hour forecasts.
- **Manual or Voice Input**: Accepts city names either through manual input or voice commands.

### Requirements
- Python 3.x
- `pyowm`
- `pyttsx3`
- `speech_recognition`
- `certifi` (Optional: Ensure secure connections)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/weather-ai.git
   cd weather-ai
   ```
2. Install the required dependencies:
   ```bash
   pip install pyowm pyttsx3 speechrecognition certifi
   ```
3. Replace the placeholder API key with your own OpenWeatherMap API key in the script.

### Usage
1. Run the script:
   ```bash
   python weather_ai.py
   ```
2. Follow the voice prompts to provide city information, temperature scale, and forecast preference.

---

## Version 2: Command-Line Weather App

### Overview
This version is a straightforward command-line application that fetches and displays weather information for a specified city. It does not include voice interaction but provides the necessary weather details directly in the console.

### Features
- **Simple Command-Line Interface**: Input city name and temperature scale through the command line.
- **Current Weather Information**: Retrieves and displays weather data including temperature, pressure, humidity, weather description, and wind speed.

### Requirements
- Python 3.x
- `pyowm`
- `certifi` (Optional: Ensure secure connections)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/weather-cli.git
   cd weather-cli
   ```
2. Install the required dependencies:
   ```bash
   pip install pyowm certifi
   ```
3. Replace the placeholder API key with your own OpenWeatherMap API key in the script.

### Usage
1. Run the script:
   ```bash
   python weather_cli.py
   ```
2. Input the city name and select the temperature scale (Celsius or Fahrenheit) when prompted.

---

Feel free to modify these descriptions to better fit the specifics of your projects!
