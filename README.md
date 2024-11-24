# AutoScout24 Scraper: Extract Car Listings with Detailed Information
## Overview
This project is a powerful car data scraper that extracts detailed car listings from two popular websites:

-AutoScout24
-Mobile.de

It automates the process of gathering essential car details, including model, price, mileage, and location, and organizes the data into a well-structured Excel file. With user-friendly formatting and clear identification of the data source, this script is designed to save time and ensure accuracy.

## Features
-Multi-Source Scraping: Collects data from both AutoScout24 and Mobile.de simultaneously.
-Extracts Essential Details:
  - **Model**
  - **Price**
  - **Mileage** (Handles missing values: marked as "KM Yok")
  - **Location**
- Outputs data to a **well-formatted Excel file**:
  - Automatically adjusts column widths for better readability.
  - Customized colors for headers and rows.
  - Highlights missing mileage data with a different color.
- Adaptable to other car brands and models by simply changing the URL.
## Example Output
Below is an example of the formatted Excel file generated by this script:
You can download the sample Excel file here: https://github.com/persates/Car_Take_Data/tree/main/asset


## How to Use
1. **Clone this repository:** git clone https://github.com/yourusername/AutoScout24-Scraper.git  
2. **Install the required Python libraries:** pip install selenium openpyxl pandas webdriver-manager
3. **Update the target URLs in the code:** driver.get("https://www.autoscout24.com.tr/lst/bmw/i7") and driver.get("https://suchen.mobile.de/fahrzeuge/search.html?dam=false&isSearchRequest=true&ms=3500%3B336%3B%3B&ref=quickSearch&s=Car&sb=rel&vc=Car")
4. **Run the script:** python autoscout24_scraper.py


## Dependencies
- Python 3.7+
- Selenium
- Pandas
- OpenPyXL
- WebDriver-Manager
## Contributions
Feel free to fork this repository and enhance it by:
- Adding support for additional websites.
- Implementing new features such as data visualization.
- Improving code performance or error handling.

Please submit a pull request with detailed changes.


## License
This project is licensed under the MIT License. See the `LICENSE` file for details.




