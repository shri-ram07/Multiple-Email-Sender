# Multiple-Email-Sender
# Bulk Email Sender

This Python script allows users to send emails to multiple recipients listed in an Excel file using the SMTP (Simple Mail Transfer Protocol) library.

## Features
- Read email addresses from an Excel file using the pandas library.
- Send emails using the Gmail SMTP server.
- Encrypt the connection using TLS (Transport Layer Security).
- Login and authenticate with your email account.
- Customize the email subject and message.

## Requirements
- Python 3.x
- pandas library: `pip install pandas`
- openpyxl library (for reading .xlsx files): `pip install openpyxl`
- smtplib library (included in Python standard library)

## Usage

1. Clone the repository or download the script file.
2. Make sure you have all the required libraries installed.
3. Update the `path_of_exelfile` variable to point to the path of your Excel file.
4. Run the script and enter your email credentials when prompted.


## Notes
1. Ensure that you have less secure apps enabled for your Gmail account or use an app-specific password.

2. The script assumes that the Excel file has an Email column with the email addresses of the recipients.
