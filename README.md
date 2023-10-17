# SMS Sender from MS Excel Sheet using eBulkSMS API

## Overview

This Python script is designed to send SMS messages using the eBulkSMS API. It reads phone numbers and account balances from an Excel file and sends customized SMS messages to each recipient. The script handles exceptions, ensuring robustness by catching and reporting errors that may occur during the process. This project serves as a practical example of using the `requests` library to interact with a web API and `openpyxl` to work with Excel files, making it a useful tool for automating SMS notifications or alerts based on data stored in an Excel spreadsheet.

## Features

- Send SMS messages using the eBulkSMS API.
- Read phone numbers and account balances from an Excel file.
- Customize SMS messages for each recipient.
- Handle exceptions and report errors for a robust operation.

## Prerequisites

Before using this script, make sure you have the following:

- Python (3.x) installed on your system.
- Required Python libraries: `requests` and `openpyxl`. You can install them using `pip`:
  
## Usage

1. Clone this repository to your local machine or download the script directly.
2. Ensure you have an Excel file with phone numbers and account balances.
3. Update the script to include your eBulkSMS API credentials and customize the SMS messages.
4. Run the script using the following command:
5. The script will read data from the Excel file, send SMS messages, and handle exceptions.

## Configuration

Before running the script, you need to configure the following:

- Replace `YOUR_API_KEY` and `YOUR_API_SECRET` with your eBulkSMS API credentials in the script.
- Customize the SMS message in the script to meet your specific requirements.
- Make sure the Excel file is in the same directory as the script or provide the correct file path.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- This script is created as a practical example and can be used as a foundation for building more complex SMS automation systems.

Happy SMS sending!


