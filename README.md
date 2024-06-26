# Weather Dashboard
![](WEATHER-DASHBOARD.gif)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [License](#license)

## Overview
The Weather Dashboard is a web application that allows users to search for weather information in any city. It displays the current weather and a 5-day forecast, and saves search history with the option to delete previous searches.

## Features
- Search for current weather and 5-day forecast by city name.
- Display temperature, wind speed, and humidity.
- Save searched cities in local storage and display them as buttons.
- Delete previously searched cities from the history.

## Getting Started
Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- Web browser (e.g., Google Chrome, Firefox)
- Text editor (e.g., VS Code)
- Internet connection

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/ElijahWard4/Weather-Dashboard.git
    ```
2. Open the project directory:
    ```bash
    cd Weather-Dashboard
    ```
3. Open index.html in your web browser or use a live server extension in your text editor.

### Configuration
Replace the placeholder API key in script.js with your own OpenWeather API key:
```javascript
const apiKey = `YOUR_OPENWEATHER_API_KEY`;
```

## Usage
1. Open the application in your web browser.
2. Enter the name of a city in the search bar and click the "Search" button.
3. View the current weather and 5-day forecast for the city.
4. Previously searched cities will appear as buttons in the sidebar. Click these buttons to quickly view the weather for those cities again.
5. Use the "Delete" button under each city in the history to remove it from the list.

## Technologies Used
- HTML
- CSS
- JavaScript
- OpenWeather API

## License
This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to contribute to this project by submitting issues or pull requests. If you have any questions, please contact [elijah.ward014@gmail.com]. Happy coding!
