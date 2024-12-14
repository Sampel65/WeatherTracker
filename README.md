Objective

The Weather Tracker app is a SwiftUI-based iOS application that allows users to search for a city 
and view its weather details such as temperature, 
weather conditions, humidity, UV index, and "feels like" temperature. 
The selected city is persisted across app launches, and the UI follows the Figma design closely.


Features
Splash Screen
Home Screen:
Displays weather for a single saved city, including:
City name
Temperature
Weather condition (with corresponding icon)
Humidity (%)
UV index
"Feels like" temperature
If no city is saved, users are prompted to search for a city.

Search Screen:
Allows users to search for cities and display their weather.
Tapping on a search result updates the ContentView Screen with the selected city's weather.
The selected city is persisted and reloaded on subsequent launches.

Tech Stack
Swift (for native iOS development)
SwiftUI (for building the UI)
WeatherAPI.com (for fetching weather data)
UserDefaults (for local persistence of the selected city)
MVVM architecture (for clean, modular, and testable code)
Protocol-Oriented Programming and Dependency Injection<img width="692" alt="Screenshot 2024-12-14 at 17 51 22" src="https://github.com/user-attachments/assets/9585b456-d729-4c0b-aa96-e07e610bcdeb" />


<img width="692" alt="Screenshot 2024-12-14 at 17 51 07" src="https://github.com/user-attachments/assets/3821e3b5-c56d-4d5c-8699-df4f85c3c1d7" />
<img width="692" alt="Screenshot 2024-12-14 at 17 51 32" src="https://github.com/user-attachments/assets/9a4e3ee1-b06e-42fa-a581-8242ba81b78f" />


https://github.com/user-attachments/assets/cf3c8baf-4912-4c27-bd1c-39aa125707f9



https://github.com/user-attachments/assets/e912cb59-bb4f-4a67-8e2b-81a898c8437f

