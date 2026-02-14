Weather App ☀️🌧️❄️
A simple and elegant desktop weather application built with Python (PyQt5).
Enter any city name to get real-time temperature, weather conditions, and an emoji icon that visually represents the forecast.
Example:  
 |  Enter city name:  Bur Dubai  |  
 |  ☀️  |  
 |  73°F  |  
 |  clear sky  |

<img width="466" height="565" alt="Screenshot 2026-02-14 at 5 31 07 PM" src="https://github.com/user-attachments/assets/e151d3a8-e6c9-42d5-939d-d0c16ea883a2" />


🚀 Features
Clean and responsive PyQt5 GUI

Real-time weather data using the OpenWeatherMap API

Emoji-based weather icons (e.g., ☀️ 🌧️ ❄️ 🌪️)

Supports error handling for most HTTP and network errors

Temperature displayed in Fahrenheit (also calculates °C internally)

🛠️ Requirements
Make sure you have the following installed:

Python 3.8 or higher

PyQt5

Requests library

Install dependencies using:

bash
pip install PyQt5 requests
⚙️ Setup & Usage
Clone the repository:

bash
git clone https://github.com/yourusername/weather-app.git
cd weather-app
Get an API key from OpenWeatherMap.

Edit the code:
Open the file and replace this line with your API key:

python
api_key = "your_api_key"
Run the app:

bash
python weather_app.py
📋 Error Handling
This app includes detailed error messages for:

Invalid API key (401 Unauthorized)

City not found (404 Not Found)

Server downtime or connection issues

Timeout and redirection errors

🌈 Example Weather Icons
Condition	Emoji	Description
Thunderstorm	⛈️	200–232
Drizzle	🌦️	300–321
Rain	🌧️	500–531
Snow	❄️	600–622
Fog	🌁	701–741
Clear	☀️	800
Clouds	☁️	801–804
Tornado	🌪️	781
🤝 Credits
OpenWeatherMap API for real-time weather data

PyQt5 for GUI design

Emoji icons from Unicode Standard

