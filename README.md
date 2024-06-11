# Exchange Rate Data Retrieval and Analysis

This Python project utilizes the Frankfurter API along with Python libraries such as Pandas, Requests, and Matplotlib to retrieve exchange rate data, perform data preprocessing, exploratory data analysis (EDA), and analyze currency relationships.

## Technologies Used

- Python
- Pandas
- Requests
- Matplotlib

## Features

1. **Data Retrieval:** Exchange rate data is retrieved from the Frankfurter API using the Requests library.
2. **Data Preprocessing:** Raw data is processed and cleaned using Pandas to ensure quality for analysis (Converts the JSON response from the API into a Pandas DataFrame for easy manipulation and analysis).
3. **Exploratory Data Analysis (EDA):** Various statistical and visual analyses are performed to gain insights into the dataset.
4. **Currency Relationship Analysis:** Relationships between different currencies are explored and analyzed using mathematical and statistical techniques.

## Installation

1. Clone the repository:
git clone <https://github.com/Ogoms/Exchange-Rate-Data-Retrieval-with-Frankfurter-API.git>


2. Install the required dependencies:

pip install -r requirements.txt


3. Run the main script:

python Exchange-Rate-Data-Retrieval.ipynb


## Usage

- Modify the parameters in the `main.py` script to customize data retrieval and analysis.
- Explore the Jupyter Notebook files for detailed analysis and visualization examples.

## Contributors

- [Your Name](https://github.com/your_username)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.







# **Exchange Rate Data Retrieval with Frankfurter API**
This Python script retrieves historical exchange rate data from the Frankfurter API for a specified date range. It utilizes the requests library to send HTTP requests to the API and fetches the data in JSON format. The retrieved data is then converted into a Pandas DataFrame for further analysis and processing.

## **Overview**
The Exchange Rate Data Retrieval script provides a convenient way to access historical exchange rate information for various currencies. It can be used for financial analysis, currency conversion, and trend analysis.

## **Features**
Data Retrieval: Fetches historical exchange rate data from the Frankfurter API for a specified date range.
Data Processing: Converts the JSON response from the API into a Pandas DataFrame for easy manipulation and analysis.
Customization: Allows users to specify the date range for which they want to retrieve exchange rate data.
## **Installation**

## **Usage**
Install required libraries:
!pip install requests

Run the Python script:
import requests
import pandas as pd
from pandas import json_normalize

api_url ='https://api.frankfurter.app/2013-01-01..2023-08-31'

response = requests.get(api_url)
data = response.json()

Access the data in the data dictionary and process it as needed.
## **Contributing**
Contributions to this project are welcome! If you would like to contribute, please fork the repository and submit a pull request with your changes.
## **License**
This project is licensed under the MIT License - see the LICENSE file for details.
## **Contact**
For any inquiries or suggestions, please contact Ogoms at https://github.com/Ogoms/Exchange-Rate-Data-Retrieval-with-Frankfurter-API
