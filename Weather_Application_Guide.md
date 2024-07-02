
# Weather Application

## Introduction

This Weather Application is a Python-based project that provides current weather information for a specified location. It uses the OpenWeatherMap API to fetch real-time weather data and displays it in a user-friendly interface.

## Project Structure

The project contains the following main components:

- `weather_report.py`: A script to generate weather reports.
- `weather_app/WeatherApp.py`: The main application script.
- `weather_app/main.py`: Entry point for the application.
- `weather_app/main.ui`: UI design file.
- `weather_app/owm.py`: Module to interact with the OpenWeatherMap API.
- `weather_app/SampleOutput.png`: A sample output image.

## Requirements

To run this application, you need to have the following installed:

- Python 3.x
- PyQt5 (for the graphical user interface)
- Requests (for API requests)

You can install the required Python packages using pip:

\`\`\`bash
pip install pyqt5 requests
\`\`\`

## Getting Started

1. **Clone the Repository**

   Clone the repository to your local machine using the following command:

   \`\`\`bash
   git clone https://github.com/your-repo/weather-app.git
   \`\`\`

2. **Navigate to the Project Directory**

   \`\`\`bash
   cd weather-app/weather_app
   \`\`\`

3. **Run the Application**

   You can start the application by running the `main.py` script:

   \`\`\`bash
   python main.py
   \`\`\`

## Application Overview

### WeatherApp.py

This is the main application script that sets up the GUI and handles user interactions. It uses PyQt5 to create a graphical interface and integrates with the OpenWeatherMap API to fetch weather data.

### main.py

This script serves as the entry point for the application. It initializes the `WeatherApp` class and starts the PyQt5 event loop.

### owm.py

The `owm.py` module contains functions to interact with the OpenWeatherMap API. It includes methods to fetch current weather data based on the user-provided location.

### main.ui

The `main.ui` file is a Qt Designer file that defines the layout and design of the application's user interface.

### Sample Output

![Sample Output](weather_app/SampleOutput.png)

## Conclusion

This Weather Application provides a simple yet effective way to check the current weather conditions for any location. It's a great project for learning about API integration and GUI development in Python.

Feel free to contribute to the project by forking the repository and submitting pull requests.
