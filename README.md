# Flutter-Weather-App
This is a cross-platform weather application built using Flutter and Dart, featuring a clean and modern UI inspired by weather app design concepts from Dribbble. It fetches real-time weather data from OpenWeatherMap and displays:

Current weather by location

Hourly forecasts

7-day weather overview

Searchable cities

🔧 The app is compatible with both Android and iOS.

🔥 Features
🌍 Automatically fetches user location using device GPS

🔎 Location-based search support

🌦️ Real-time hourly and daily weather forecasts

🎨 Stylish and responsive UI (inspired by modern weather app designs)

🌐 Consumes RESTful APIs (OpenWeatherMap)

🔧 Technologies Used
Flutter 3.0+

Dart

OpenWeatherMap API v2.5

Provider (for state management)

Geolocator (for fetching location)

📦 How to Run the App
Get an API Key from OpenWeatherMap
👉 Sign up at https://openweathermap.org/
👉 Go to: https://home.openweathermap.org/api_keys

Verify your API key is working
Paste this in your browser with your API key:

bash
Copy
Edit
https://api.openweathermap.org/data/2.5/weather?lat=53.4794892&lon=-2.2451148&units=metric&appid=YOUR_API_KEY
Clone the Repository

sh
Copy
Edit
git clone https://github.com/your-username/flutter_weather_app.git
cd flutter_weather_app
Install Dependencies

sh
Copy
Edit
flutter pub get
Add Your API Key
Open lib/provider/weatherProvider.dart and replace:

dart
Copy
Edit
String apiKey = 'Paste Your API Key Here';
Run the App

sh
Copy
Edit
flutter run
