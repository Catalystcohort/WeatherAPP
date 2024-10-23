<h1>WeatherApp for Indian Cities</h1>
    <p>Welcome to WeatherApp, a simple application that provides real-time weather information for various cities in India.</p>

  <h2>Features</h2>
    <ul>
        <li>Real-time weather data for multiple Indian cities.</li>
        <li>Temperature, humidity, and weather conditions.</li>
        <li>Easy to use and intuitive interface.</li>
    </ul>

   <h2>Technologies Used</h2>
    <ul>
        <li>HTML, CSS, and JavaScript for front-end development.</li>
        <li>OpenWeatherMap API for fetching weather data.</li>
        <li>Responsive design for mobile and desktop views.</li>
    </ul>
    <h2>Getting Started</h2>
    <p>To run the WeatherApp locally, follow these steps:</p>
    <ol>
        <li>Clone the repository to your local machine:</li>
        <pre><code>git clone https://github.com/yourusername/weatherapp.git</code></pre>

   <li>Navigate to the project directory:</li>
        <pre><code>cd weatherapp</code></pre>
    <li>Open the <code>index.html</code> file in your web browser.</li>
    </ol>

   <h2>Using the Application</h2>
    <p>1. Enter the name of an Indian city in the search bar.</p>
    <p>2. Click the "Get Weather" button.</p>
    <p>3. View the current weather data displayed on the screen.</p>

 <h2>API Key Configuration</h2>
    <p>To use the OpenWeatherMap API, you need to obtain an API key:</p>
    <ol>
        <li>Sign up at <a href="https://openweathermap.org" target="_blank">OpenWeatherMap</a>.</li>
        <li>Navigate to your API keys section and copy your API key.</li>
        <li>Replace <code>YOUR_API_KEY</code> in the JavaScript code with your actual API key.</li>
    </ol>

   <h2>Example API Call</h2>
    <p>The application fetches weather data using the following API endpoint:</p>
    <pre><code>https://api.openweathermap.org/data/2.5/weather?q={city_name},IN&appid=YOUR_API_KEY</code></pre>

   <h2>License</h2>
    <p>This project is licensed under the MIT License.</p>
