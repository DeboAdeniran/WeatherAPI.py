🌤️ Weather App (PyQt5)
A simple GUI-based Weather App built with Python and PyQt5, using the OpenWeatherMap API to fetch real-time weather data.

🚀 Features
🌡️ Fetches real-time weather data for any city.
🌍 Displays temperature in Fahrenheit.
😊 Shows an emoji representation of the weather condition.
📜 Handles various errors like invalid cities, network issues, and API errors.
🛠️ Installation
Prerequisites
Python 3.x installed
Required dependencies: requests, PyQt5
Install Dependencies
Run the following command:

sh
Copy
Edit
pip install requests PyQt5
⚙️ Usage
Clone the repository:

sh
Copy
Edit
git clone https://github.com/YourUsername/WeatherAPI.py.git
cd WeatherAPI.py
Run the script:

sh
Copy
Edit
python weather.py
Enter a city name and click "Get Weather" to see the weather details.

🌎 API Key
This app uses the OpenWeatherMap API. Make sure you replace api_key in get_weather() with your own API key.

Get a free API key from: OpenWeatherMap

Replace the placeholder in weather.py:

python
Copy
Edit
api_key = "YOUR_API_KEY_HERE"
🛑 Error Handling
Shows error messages for invalid cities or network issues.
Handles different HTTP errors gracefully.
📜 License
This project is MIT licensed.
