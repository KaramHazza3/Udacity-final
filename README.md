# Travel App

## Overview
The Travel Planner App is a web application that allows users to plan their trips by entering a destination and departure date. The app fetches information about the destination, including images and weather details, and displays it to the user. Users can also delete trips from the list.

## Features
- Add a trip with a destination and departure date.
- Fetch and display destination images from Pixabay.
- Fetch and display weather data from Weatherbit.
- Display a list of planned trips with options to delete them.

## Technologies Used
- HTML
- CSS
- JavaScript
- Node.js
- Express
- Axios
- Webpack

## API Dependencies
- GeoNames API
- Pixabay API
- Weatherbit API

## Installation
1. **Clone the Repository**
    ```bash
    git clone https://github.com/KaramHazza3/Udacity-final.git
    ```   

2. **Switch to the `master` Branch**
    ```bash
    git checkout master
    ```

3. **Install Dependencies**
    Install all the required dependencies using npm:
    ```bash
    npm install
    ```

4. **Ensure Environment Variables are Set**
    Create a `.env` file in the root directory and add the following environment variables:
    ```bash
    PORT=1000
    GEONAMES_USERNAME=your_geonames_username
    PIXABAY_API_KEY=your_pixabay_api_key
    WEATHERBIT_API_KEY=your_weatherbit_api_key
    ```
    Replace `your_geonames_username`, `your_pixabay_api_key`, and `your_weatherbit_api_key` with your actual API credentials.

## Running the Application

1. **Start the Development Server**
    Run the following command to start the development server:
    ```bash
    npm run build-dev
    ```
    This should compile your application and start the Webpack development server.

2. **Building for Production**
    To build the project for production, use:
    ```bash
    npm run build-prod
    ```
    This will create a `dist` folder with your production-ready application.

3. **Start the server**
    ```bash
    npm run start
    ```

4. **Open your browser and go to**
    ```bash
    http://localhost:1000/
    ```

## Contributing
- If you would like to contribute to this project, please fork the repository and create a pull request with your changes.

## Troubleshooting
- **Issue with API keys**: Ensure you have valid API keys for GeoNames, Pixabay, and Weatherbit, and that they are correctly set in your `.env` file.
- **Server not starting**: Verify that Node.js is correctly installed, and check the terminal for any error messages that could indicate missing dependencies or configuration issues.
- **Missing .env file**: Ensure the `.env` file exists and contains all required environment variables.

## Node.js Version
This project requires **Node.js v18 or later**. Ensure you have the correct version installed by running:
```bash
node -v
```

