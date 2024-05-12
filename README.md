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