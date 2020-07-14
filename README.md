# Import YouTube playlist to Google Spreadsheet
a small Python script that lists a youtube playlist into a google spreadsheet

## How to use ?
requires python 3 with [pip](https://pypi.org/project/pip/)
To run the source code, you need google-api-python-client, gspread, and oauth2client

Steps:

Go to the Google APIs Console. https://console.developers.google.com/

Create a new project and give it some name.

Click "Enable API". 

Search for and enable the "Google Sheets API".

Create credentials for a "Web Server" to access "Application Data".

Click "What credentials do i need" button to set up credentials.

Name the service account and grant it a Project Role of "Editor" and key type as "JSON".

Download the JSON file to your main.py code directory and rename it to client.secret.json

Create a gooogle spreadsheet where you want the playlist and share with the service account email id created above with "Edit" rights

Enable Youtube Data v3 API

You will get the OAuth2 token.

Copy the API key into a notepad file named "client.secret.txt"

Both the json and txt files must be with main.py

Install required modules with: pip install google-api-python-client gspread oauth2client

Run main.py. You'll need to give the youtube playlist ID and the ID of the spreadsheet

