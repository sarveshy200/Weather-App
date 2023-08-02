# Weather App with API Integration (HTML, CSS, JavaScript)

The Weather App is a simple web application that allows users to search for weather information for different cities using an external API. It provides real-time weather data, such as temperature, humidity, wind speed, and weather conditions, for any city specified by the user.
First Page
<img width="960" alt="Screenshot 2023-08-02 164313" src="https://github.com/sarveshy200/Weather-App/assets/105293807/caaecafd-a213-44eb-83a6-b76f109e746b">
Second Page
<img width="947" alt="Screenshot 2023-08-02 165126" src="https://github.com/sarveshy200/Weather-App/assets/105293807/3ae3b7fd-4064-4019-807b-e23f87f0175b">


## How to Use

1. **Clone the repository**

   ```
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```

2. **Obtain an API key**

   To fetch weather data, you'll need an API key from a weather service provider. The app uses the OpenWeatherMap API by default, but you can choose a different provider if you prefer. Sign up on the provider's website and obtain an API key.

3. **Configure the API key**

   Open the `index.js` file in the project's root directory. Look for the `API_KEY` variable near the top of the file and replace `'YOUR_API_KEY'` with your actual API key.

   ```javascript
   const API_KEY = 'YOUR_API_KEY';
   ```

4. **Run the app**

   The Weather App consists of three files: `index.html`, `styles.css`, and `index.js`. To run the app, simply open the `index.html` file in your preferred web browser.

   You can also use a local development server like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) (if you use Visual Studio Code) to serve the files and view the app in your browser.

5. **Start using the Weather App**

   Once you open the app in your browser, you can enter the name of any city in the search bar, and the app will fetch and display the current weather information for that location.

## Technologies Used

- HTML: The markup language used for the structure of the app.
- CSS: Styling the components and making the app visually appealing.
- JavaScript: Handling API requests and updating the DOM with weather data.

## API Used

- The Weather App uses the OpenWeatherMap API to fetch weather data for different locations. Make sure you have a valid API key to use the service.

## Contributing

Contributions to this Weather App are welcome! If you find a bug or want to add a new feature, please feel free to open an issue or submit a pull request.

## License

The Weather App is open-source software licensed under the [MIT License](LICENSE).

## Acknowledgments

- This Weather App was created for educational purposes and is not intended for commercial use.
- Thanks to OpenWeatherMap for providing the API to fetch weather data.
