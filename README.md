# Gmail Spammer

## Overview
This project, "Gmail Spammer," is designed to automate the process of sending a specified number of emails to a targeted email address using Gmail. It's important to emphasize that this tool is intended strictly for educational and experimental purposes. It should never be used for malicious activities or to harm others. Misuse of this tool could violate laws and Gmail's terms of service.

## Prerequisites
- Basic knowledge of Python and working with APIs.
- A Google account with Gmail enabled.

## Legal Disclaimer
This project is for educational purposes only. The developer assumes no liability and is not responsible for any misuse or damage caused by this program.

## Setup and Installation

### Step 1: Create a New Gmail Account
Create a new Gmail account that will be used to send emails. 

### Step 2: Google Cloud Console Setup
- Go to the [Google Cloud Console](https://console.cloud.google.com/).
- Create a new project.
- Enable the Gmail API for your project.

### Step 3: API Credentials
- In the Google Cloud Console, navigate to APIs & Services.
- Set up the OAuth consent screen.
- Create an OAuth Client ID.
- Download the `credentials.json` file.

### Step 4: Project Setup
- Place the `credentials.json` file in the same directory as `main.py`.
- Install necessary Python packages:
  `pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib`

### Step 5: Configuration
- Open `main.py`.
- Modify the variables as needed:
- `email_count`: Number of emails to be sent.
- `sender_email`: The Gmail address you created for sending emails.
- `to_email`: Target email address.

## Usage
Run the script from your command line or IDE. Ensure you have Internet connectivity and that your Google Cloud Console setup is correctly configured.

## Contributing
Contributions to this project are welcome, especially those that improve its educational value or extend its functionality in a responsible manner.

## License
GNU General Public License v3.0
