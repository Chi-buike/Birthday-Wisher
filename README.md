# Birthday Wisher 🎉

This is a Python automation project that sends birthday emails to people based on data stored in a CSV file. The script randomly selects a letter template, replaces the placeholder with the person's name, and sends the message using SMTP.

## Features
- Reads birthdays from a CSV file
- Automatically checks if today matches someone's birthday
- Randomly selects from 3 birthday letter templates
- Sends an email to the birthday person

## Technologies Used
- Python
- Pandas
- SMTP
- Git & GitHub

## How to Run
 Run: `python main.py`

## Security Reminder
This project currently uses hardcoded email credentials, but best practice is to store passwords in environment variables instead of inside your code.

