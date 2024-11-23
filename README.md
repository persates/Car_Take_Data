# AutoScout24 Scraper: Extract Car Listings with Detailed Information
## Overview
This Python project scrapes car listing data from websites like AutoScout24 and organizes the data into a formatted Excel file. It extracts key details such as model, price, mileage, and location, with options to handle missing data and apply advanced formatting.

## Features
- Extracts essential details:
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
You can download the sample Excel file here: [Cari7.xlsx](https://github.com/persates/Car_Take_Data/asset/main/Cari7.xlsx)


## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/AutoScout24-Scraper.git
  Install the required Python libraries: 
-pip install selenium openpyxl pandas webdriver-manager
Update the target URL in the code to the desired car listing page:
-driver.get("https://www.autoscout24.com.tr/lst/bmw/i7")
Run the script:
python autoscout24_scraper.py

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
