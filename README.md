# 🌦️ Weather App (Tkinter)

## 📖 Description
This is a small desktop application that shows the current weather of any city entered by the user.  
It is built using Python with Tkinter for the interface and the OpenWeatherMap API to fetch live weather data.

## ✨ Features
- Clean and easy-to-use interface  
- Fetches real-time weather updates  
- Shows city name, country, temperature in Celsius, and weather condition  
- Displays error messages if the city name is invalid  

## 🛠️ Technologies Used
- Python 3  
- Tkinter (for building the GUI)  
- Requests library (to connect with the API)  
- OpenWeatherMap API  

## ⚙️ How the System Works
1. The user types a city name in the input box.  
2. After clicking the **"Search to know Weather"** button, the app sends a request to the OpenWeatherMap API.  
3. The API response is processed and the following details are displayed on the screen:  
   - Location (City and Country)  
   - Temperature (converted from Kelvin to Celsius)  
   - Weather description (e.g., Clear sky, Rain, Clouds)  
4. If the city name is not found, the program shows an error popup.  

## 🎯 Learning Outcome
- Learned how to integrate external APIs in a Python project  
- Understood the basics of working with JSON responses  
- Improved skills in building desktop GUIs using Tkinter  
- Gained experience in handling user input and errors  