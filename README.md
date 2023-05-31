# Flipkart Review Scraper
This web application allows users to search for products on Flipkart and retrieve customer reviews. It utilizes web scraping techniques to automate the extraction of reviews and presents them in a user-friendly interface.

## Features
User-friendly interface for searching Flipkart products and viewing customer reviews.
Automated web scraping to extract product details and reviews from Flipkart.
Log file to record important events and errors during the scraping process.
Cross-Origin Resource Sharing (CORS) handling to retrieve data from Flipkart.
## Installation
1. Clone the repository: `git clone https://github.com/<your-username>/flipkart-review-scraper.git`
2. Navigate to the project directory: `cd flipkart-review-scraper`
3. Install the required dependencies: `pip install -r requirements.txt`
## Usage
1. Run the Flask application: python app.py
2. Access the application in your web browser at http://localhost:5000.
3. Enter a search query for the desired product.
4. View the extracted customer reviews and product details.
## Technologies/Libraries Used
1. Flask: Python web framework for building the application.
2. BeautifulSoup: Library for parsing HTML and extracting data.
3. Requests: Library for sending HTTP requests and retrieving web pages.
4. Flask-CORS: Extension for handling Cross-Origin Resource Sharing.
5. Logging: Python module for logging events and errors.
## Future Improvements
- Implement user authentication to personalize the experience.
- Expand the application to scrape reviews from other e-commerce platforms.
- Integrate sentiment analysis for a more comprehensive review analysis.
- Improve error handling and user feedback.
## Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
