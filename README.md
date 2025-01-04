# Weather Forecast Data App

This Python application provides weather forecasts, including temperature and sky conditions, for the next 1 to 5 days through a simple and interactive interface.

## Prerequisites

Python 3.x

Streamlit

Plotly

Requests (installed via requirements.txt)

## Usage

1. Clone the repository or download the files: Main.py, Backend.py, images/, and requirements.txt.

2. Install all dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Streamlit app:

```bash
streamlit run Main.py
```

## Description

* `Main.py`: The main Streamlit application that provides the user interface for weather forecasts.

* `Backend.py`: Contains the logic for fetching weather data from the OpenWeatherMap API.

* `images/`: Directory containing icons representing various sky conditions (e.g., clear, cloudy, rainy, snowy).

* `requirements.txt`: List of all required Python packages.

## How It Works

1. Users enter a city name and select the number of forecast days (1-5) through the Streamlit interface.

2. The app retrieves weather data from the OpenWeatherMap API and displays it based on user preferences:

  **Temperature**: A line graph shows the temperature trend over the selected days.

  **Sky Conditions**: Icons representing weather conditions (clear, cloudy, rainy, snowy) for each day.

3. Error handling ensures user-friendly feedback for invalid city names.

   ![image](https://github.com/user-attachments/assets/90699a0a-2834-4ec9-ad72-268e38f8be50)

## Configuration

* API_KEY in Backend.py must be set to a valid OpenWeatherMap API key.

* Ensure that the images/ directory contains the necessary icons: clear.png, cloud.png, rain.png, and snow.png.

* Modify the API URL or parameters in Backend.py as needed for additional data or customizations.

## Note

* The app is designed to provide a quick and interactive way to check weather forecasts.

* Ensure that all required Python packages are installed and that the OpenWeatherMap API key is valid.

* Customize the app to include additional weather parameters or enhanced visualizations as needed.

## Author 

Priya Patel 

Github: priyap243

