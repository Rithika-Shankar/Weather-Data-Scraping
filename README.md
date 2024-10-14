# Weather Data Scraping

## Description
In this project, I built a web scraper using **BeautifulSoup** to extract a 10-day weather forecast from a weather website. The scraper collects data such as dates, high and low temperatures, humidity, and wind speed, which are saved in a CSV file for analysis or forecasting purposes.

## Installation
1. Ensure you have Python installed on your machine.
2. Install the required libraries:
   ```bash
   pip install beautifulsoup4 requests pandas
   
## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Rithika-Shankar/weather-data-scraping.git
2. Navigate to the project directory:
   ```bash
   cd weather-data-scraping
3. Run the script:
   ```bash
   python scrape_weather.py

## Output
The weather data is saved in a file called weather_data.csv. The file contains the following columns:

- Date: The date of the forecast.
- Location: The location for which the weather is being reported.
- Condition: The weather condition for the day.
- High Temp: The highest temperature for the day.
- Low Temp: The lowest temperature for the day.
- Humidity: The humidity percentage for the day.

## Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- BeautifulSoup: For web scraping functionality.
- requests: For making HTTP requests.
- pandas: For data manipulation and storage.
