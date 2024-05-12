# ISS Tracker and Notifier 

## Description
Get notified when the International Space Station (ISS) is overhead your location during nighttime :) 🛰️

## Features
- Checks if the ISS is near your current position.
- Determines if it's nighttime at your location.
- Sends email notification to look up when ISS is overhead during nighttime.

## Setup
1. Replace placeholders in the script (`___YOUR_EMAIL_HERE___`, `___YOUR_PASSWORD_HERE___`, `__YOUR_SMTP_ADDRESS_HERE___`) with your email credentials and SMTP server address.
2. Update `MY_LAT` and `MY_LONG` with your latitude and longitude coordinates respectively. You can use [this website](https://www.latlong.net), do not forget to include "-" if it exists in front of your coordinates.

## Dependencies
- Python 3.x
- `requests` library
- `smtplib` library

## Usage
1. Run the script.
2. It continuously checks every 2 minutes if the ISS is overhead and if it's nighttime.
3. Receives email notification when conditions are met.
