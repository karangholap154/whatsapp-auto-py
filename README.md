# WhatsApp Automation Script

A Python script that uses the Twilio API to send WhatsApp messages at a scheduled time.

## Table of Contents

*   [Prerequisites](#prerequisites)
*   [Setup](#setup)
*   [Usage](#usage)
*   [Example](#example)
*   [Troubleshooting](#troubleshooting)
*   [API Documentation](#api-documentation)
*   [Changelog](#changelog)

## Prerequisites

*   Python 3.x installed on your system
*   Twilio account with a verified WhatsApp number
*   Twilio Account SID and Auth Token
*   `schedule` library installed (`pip install schedule`)

## Setup

1.  Install the required libraries by running `pip install twilio`
2.  Replace the `account_sid` and `auth_token` variables in the `main.py` file with your Twilio Account SID and Auth Token
3.  Make sure you have a verified WhatsApp number in your Twilio account

## Usage

1.  Run the `main.py` file using Python (e.g., `python main.py`)
2.  Enter the recipient's name, WhatsApp number, and the message body when prompted
3.  Enter the date and time you want to send the message in the format `YYYY-MM-DD HH:MM`
4.  The script will wait until the scheduled time and send the WhatsApp message

## Example

```python
# Example usage:
# python main.py
# Enter recipient's name: John Doe
# Enter recipient's WhatsApp number: +1234567890
# Enter message body: Hello, this is a test message.
# Enter date and time (YYYY-MM-DD HH:MM): 2024-03-16 14:30
```

## Troubleshooting

*   Make sure you have the correct Twilio Account SID and Auth Token
*   Ensure that the recipient's WhatsApp number is verified in your Twilio account
*   Check the date and time format to ensure it matches the required format
*   Check the `schedule` library version to ensure it is compatible with your Python version

## API Documentation

*   Twilio API documentation: https://www.twilio.com/docs
*   `schedule` library documentation: https://schedule.readthedocs.io/en/stable/

## Changelog

*   v1.0: Initial release
*   v1.1: Added support for scheduling messages
*   v1.2: Improved error handling and troubleshooting section
