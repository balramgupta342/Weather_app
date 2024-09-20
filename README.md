# Weather App 🌦️

This is a simple Weather App built using **Kotlin** and the **Weather API**. It provides real-time weather information based on the city name the user enters. The app displays data such as temperature, humidity, wind speed, and more, all fetched dynamically.

## Features 🚀

- **Search by City**: Enter any city name to get real-time weather data.
- **Current Weather Information**: Displays temperature, humidity, wind speed, UV index, and more.
- **Location-based Weather**: Automatically fetches weather data for the user's current location (optional).
- **Dynamic Weather Icons**: Weather conditions are represented with appropriate icons.
- **Real-time Data**: Displays accurate and up-to-date weather information.
- **User-friendly UI**: Simple, intuitive interface with a search bar for easy navigation.

## Screenshots 📱
| ![1726856582292](https://github.com/user-attachments/assets/f088473f-c74e-43f3-b720-5b890190ea29) | ![1726856503205](https://github.com/user-attachments/assets/8138cb4a-e908-408d-93bc-c244ccf5d99f) | ![1726856553994](https://github.com/user-attachments/assets/ca83c9c1-36c2-4e36-a846-d0855ad81494) | ![1726856527629](https://github.com/user-attachments/assets/6cfff596-9468-4259-aa78-35db15db6f15) |   
|--------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------:|

## Tech Stack 🛠️

- **Programming Language**: Kotlin
- **Architecture**: MVVM (Model-View-ViewModel)
- **Weather API**: Weather API
- **User Interface**: Jetpack Compose
- **Networking**: Retrofit
- **JSON Parsing**: Gson

## Requirements 📝

- Android Studio
- Minimum SDK 21 (Android 5.0)
- Internet connection for fetching real-time data
- Weather API Key (can be obtained from [here](https://www.weatherapi.com/))

## Setup and Installation 🛠️

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   ```
2. Open the project in Android Studio.
  
3. Add your Weather API key in the res/values/strings.xml file:
   ```bash
   <string name="api_key">YOUR_API_KEY</string>
   ```
4. Build and run the app on an emulator or physical device.

## How It Works 🤖

1. The user enters a city name.
2. The app sends a request to the Weather API using Retrofit.
3. The API returns weather data, which is parsed and displayed in the app’s UI, including details such as:
     - Temperature (°C)
     - Weather condition (mist, clear, cloudy, etc.)
4. Humidity, wind speed, UV index, and more.
5. The app automatically updates the UI with the latest weather information.
