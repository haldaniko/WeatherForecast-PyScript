# Weather Forecast Script

This Python script retrieves current weather conditions and a 5-day weather forecast for a specified city using the
OpenWeatherMap API. It displays temperature, wind speed, wind direction, and weather descriptions.

## Features

- Fetch current weather conditions.
- Retrieve a 5-day weather forecast.
- Supports temperature in Celsius and wind speed in meters per second.
- Wind direction is represented in compass format.

## Installation

- First you need an OpenWeatherMap API key (you can sign up for free [here](https://openweathermap.org/api)).

```bash
git clone https://github.com/haldaniko/QRcreate-TelegramBot.git
cd QRcreate-TelegramBot

# on macOS
python3 -m venv venv
source venv/bin/activate

# on Windows
python -m venv venv
venv\Scripts\activate

pip install -r requirements.txt

(Copy .env.sample to .env and populate it with all required data.)

python weather_forecast.py
```

## Usage

Run the script from the command line with the name of the city as an argument. For example:

```bash
python weather_forecast.py "Kiev"
```