# Tinder Automation Bot

This project is a simple Tinder bot built using Python and Selenium WebDriver. It automates the process of logging into Tinder via Facebook, swiping profiles, and handling pop-ups. The script allows you to automate up to 100 profile swipes.

## Features:
- Automates login to Tinder via Facebook.
- Automates swiping right (liking) profiles.
- Handles pop-ups such as "It's a Match" or notifications.
- Can be customized to increase or decrease the number of swipes.

## Requirements:
- Python 3.x
- Selenium WebDriver
- Google Chrome Browser and ChromeDriver

## Installation:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/tinder-automation-bot.git


Install the required libraries:

pip install selenium
Download and install ChromeDriver: Download the version of ChromeDriver that matches your installed Google Chrome browser from here.

Set up environment variables: Replace the placeholders in the script with your own credentials:

FB_EMAIL: Your Facebook login email.
FB_PASSWORD: Your Facebook password.
chrome_driver_path: The file path where ChromeDriver is installed.
Example:

python
Copy code
FB_EMAIL = "your_facebook_email"
FB_PASSWORD = "your_facebook_password"
chrome_driver_path = "path_to_your_chromedriver"
Usage:
Run the script:
python tinder_bot.py
How the script works:

The script opens Tinder in a Chrome browser.
Logs in via Facebook using your credentials.
Allows location and handles notification pop-ups.
Automatically starts swiping right on profiles.
Customization:
Swiping Limit: The script is currently set to swipe 100 times. You can change the number of swipes by modifying the for n in range(100) loop.

python
for n in range(100):
    # Your code for swiping
Troubleshooting:
Element not found errors: If you encounter NoSuchElementException, it might be because the XPaths in the script no longer match the Tinder website. You can update the XPaths by inspecting the elements on the Tinder webpage.

ChromeDriver issues: Ensure that the version of ChromeDriver you're using matches the version of Chrome installed on your system.

Legal Disclaimer:
This project is for educational purposes only. Automating interactions with Tinder may violate Tinder’s terms of service, and using this bot could result in your account being banned. Use at your own risk.


