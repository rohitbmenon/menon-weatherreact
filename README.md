# React Weather App

This is a simple React weather app that allows users to check the current weather conditions for different cities. The app utilizes the OpenWeatherAPI to fetch real-time weather data.

## Features

- **City Weather:** Search for a specific city and view its current weather details.
- **Temperature Units:** Toggle between Celsius and Fahrenheit for temperature display. Also Wind speed is given as well.
- **Responsive Design:** The app is designed to work seamlessly on both desktop and mobile devices.

## Technologies Used

- **React:** The app is built using the React library, making it fast and efficient.
- **OpenWeatherAPI:** Real-time weather data is fetched from the OpenWeatherAPI.

## Getting Started

Follow the instructions below to run the project locally on your machine.

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/react-weather-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd react-weather-app
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Create a `.env` file in the root directory and add your OpenWeatherAPI key:

    ```env
    REACT_APP_OPENWEATHER_API_KEY=your-api-key
    ```

    You can obtain an API key by signing up on the [OpenWeatherAPI website](https://openweathermap.org/api).

5. Start the development server:

    ```bash
    npm start
    ```

6. Open your browser and visit [http://localhost:3000](http://localhost:3000) to view the app.

## Usage

- Enter the name of the city in the search bar and press Enter or click the search button.
- View the current weather details for the specified city.

## Contributing

If you would like to contribute to the project, feel free to submit a pull request. Please follow the [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
