![Simulator Screenshot - iPhone 15 Pro Max - 2025-01-16 at 21 15 32](https://github.com/user-attachments/assets/61a5c312-a518-4e69-a4ea-e7c5ceee3de4)# My Meteo App

Welcome to **My Meteo App**, my first Flutter project! This app allows users to check the current weather conditions for any city by leveraging the OpenWeatherMap API.

## Features
- Beautiful, dynamic user interface.
- View weather details such as:
  - Current temperature (in Celsius).
  - Weather conditions (e.g., clear sky, rain, etc.).
  - City name.
- Navigate between the home page and detailed weather information page.
- Stunning background imagery that enhances the user experience.

## App Preview
<img src="./assets/Screenshot 2025-01-16 at 21.29.54" width="180" height="3" alt="MeteoApp Screenshot">

---

## Prerequisites
Before running this app, ensure you have the following installed:

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (version 3.10 or later recommended)
- Dart (comes with Flutter installation)
- Android Studio or VS Code with Flutter extensions
- A valid [OpenWeatherMap API key](https://openweathermap.org/api)

## Installation and Setup
Follow these steps to run the app locally:

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd my-meteo-app
   ```

3. Install the dependencies:
   ```bash
   flutter pub get
   ```

4. Run the app on an emulator or connected device:
   ```bash
   flutter run
   ```

---

## File Structure
Here is a brief overview of the app's file structure:

```
my-meteo-app/
|- assets/                     # Contains background images used in the app
|- lib/                        # Main Flutter application code
   |- main.dart                # Entry point of the application
   |- HomePage.dart            # Home page with navigation to weather details
   |- WeatherDetailPage.dart   # Fetch and display weather details
|- pubspec.yaml                # Project dependencies and metadata
```

---

## How It Works
1. The **HomePage** displays a welcome message and a button to navigate to the weather details page.
2. On the **WeatherDetailPage**, users can input a city name and fetch real-time weather data by pressing the "Fetch Weather" button.
3. The app communicates with the OpenWeatherMap API to retrieve weather information and displays it on the screen.

---

## Known Issues
- Ensure you have a stable internet connection to fetch weather data.
- The app currently supports only metric units (Celsius).

## Future Improvements
- Add more weather details, such as humidity and wind speed.
- Implement multi-language support.
- Improve responsiveness on tablets and larger screens.

---

## License
This project is licensed under the MIT License. Feel free to use it as a starting point for your own Flutter projects!

---

Thank you for trying **My Meteo App**! If you have any feedback or suggestions, feel free to reach out.

