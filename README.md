# Import YouTube playlist to Google Spreadsheet
a small Python script that lists a youtube playlist into a google spreadsheet

## How to use ?
requires python 3 with [pip](https://pypi.org/project/pip/)
To run the source code, you need gspread and oauth2client packages

*  [Google API Client](https://github.com/googleapis/google-api-python-client)
*  [GSpread](https://gspread.readthedocs.io/en/latest/)
*  [OAuth2 client](https://pypi.org/project/oauth2client/)

Go to the Google APIs Console. https://console.developers.google.com/

Create a new project and give it some name.

Click Enable API. 

Search for and enable the Google Sheets API.

Create credentials for a "Web Server" to access "Application Data".

Click What credentials do i need.

Name the service account and grant it a Project Role of "Editor" and key type JSON.

Download the JSON file to your main.py code directory and rename it to client.secret.json

Create a gooogle spreadsheet and share with the service account email created above with "Edit" rights

Enable Youtube Data v3 API

Create credentials for a Web Server to access Application Data.

Copy the API key into client.secret.txt

Both the json and txt files must be with main.py

Install pip install google-api-python-client gspread and oauth2client with: pip install pip install google-api-python-client gspread oauth2client

Run main.py. You'll need to give the youtube playlist ID and the ID of the spreadsheet

