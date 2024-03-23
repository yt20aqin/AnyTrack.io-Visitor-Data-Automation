# AnyTrack.io Visitor Data Automation

## Project Overview

This project automates the extraction of visitor data from anytrack.io, specifically focusing on capturing the date and the full URL of each visit. Designed to aid recruitment teams by identifying active job vacancies across all London boroughs, this bot facilitates regular updates and insights into market dynamics. Utilizing web scraping techniques, the system logs into anytrack.io, navigates through the visitor list, and extracts the required data, which is then systematically organized into a Google Sheets document for easy access and analysis.

### Features

- **Automated Login**: Securely logs into anytrack.io to access visitor data.
- **Data Extraction**: Extracts the date and full URL of each visitor's session highlighted within designated areas of the web interface.
- **Google Sheets Integration**: Seamlessly inputs the extracted data into a Google Sheets document, ensuring continuous updates without manual intervention.
- **Data Formatting**: Converts extracted time and date information into a specified format for consistency and ease of analysis.
- **Scheduled Runs**: Capable of being scheduled for automatic execution, ensuring the recruitment team receives timely updates on active job vacancies across London boroughs.

### Technology Stack

- **Node.js**: Serves as the core platform for running the automation script.
- **Selenium**: Used for web scraping, automation, and simulating browser activity.
- **Google Sheets API**: Facilitates the interaction with Google Sheets for data storage and manipulation.

### How It Works

1. **Initialization**: The bot initiates by logging into anytrack.io using provided credentials.
2. **Data Extraction**: It navigates the user interface, identifying and extracting the date and full URL for each visitor session.
3. **Data Processing**: Extracted data is formatted as per the specified requirements before being sent to Google Sheets.
4. **Google Sheets Update**: The bot inputs the processed data into a predefined Google Sheets document, appending new entries while maintaining historical data integrity.
5. **Scheduling**: Scheduled tasks ensure the bot runs at regular intervals, providing consistent updates to the recruitment team.

### Note

This project is designed for portfolio demonstration purposes and showcases the ability to automate complex data extraction and processing tasks. It demonstrates a practical application in streamlining recruitment processes through technological innovation.

## Disclaimer

This automation script is developed for educational and portfolio display purposes only. Users are responsible for ensuring compliance with anytrack.io's terms of service and data use policies, as well as with Google Sheets API usage regulations.
