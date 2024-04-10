## Keyword Internal Linking

### Description
This Python script performs keyword searches on a specified domain and stores the search results in a Google Sheets spreadsheet.

### Prerequisites
- Python 3.x
- Required Python libraries: `pandas`, `gspread`, `requests`, `oauth2client`
- Google account with access to Google Sheets API

### Installation
1. Install Python 3.x from [python.org](https://www.python.org/downloads/).
2. Install the required Python libraries:
   ```
   pip install pandas gspread requests oauth2client
   ```
3. Enable the Google Sheets API and obtain the service account JSON file. Instructions can be found in the [Google Sheets API documentation](https://developers.google.com/sheets/api/quickstart/python).
4. Place the service account JSON file in the same directory as the script.

### Usage
1. Run the script in your terminal or command prompt:
   ```
   python internal_linking.py
   ```
2. Enter the domain, number of URLs, and file name when prompted.
3. The script will perform keyword searches on the specified domain, fetch URLs, and update a new worksheet in the specified Google Sheets spreadsheet.

### Notes
- Ensure that the Google Sheets API is enabled and the necessary permissions are granted.
- Make sure the service account JSON file is correctly named and placed in the script directory.
- This script uses Google Custom Search Engine API for searching. Ensure that the API key and Custom Search Engine ID are valid and properly configured.
- For large datasets, consider optimizing the script for performance.
