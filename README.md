# Python-DVWA-Brute-Force
This Python script is designed for educational purposes to demonstrate and test the security of web applications. It attempts to brute-force a login page using DVWA (Damn Vulnerable Web Application) by trying different username and password combinations from a provided password file.

**Features:**
- Brute-force login attempts on DVWA login pages.
- Customizable username, password file, and login failure string.
- Educational tool for understanding web application security.

**Prerequisites:**# DVWA Login Brute-Force Script
Before you can use this script, make sure you have the following dependencies installed:

- Python 3
- The `requests` library
- The `termcolor` library

You can install the necessary libraries using `pip`:

bash
```pip install requests termcolor```

- Python 3
- Dependencies: `requests`, `termcolor`

***Usage***
Clone this repository to your local machine.

Navigate to the directory containing the script.
python brute_force.py

Run the script using the following command:

python 48-bruteforce.py

Follow the prompts to provide the required information:

Page URL: Enter the URL of the login page you want to target.
Username: Enter the username you want to brute-force.
Password File: Provide the path to a file containing a list of passwords to try.
Login Failed String: Enter a string that indicates a failed login attempt (e.g., an error message).
The script will attempt to brute-force the login page using the provided information. If it successfully finds the correct username and password, it will display them.


Disclaimer
This script is for educational purposes only. It should only be used on systems and applications that you have explicit permission to test. Unauthorized use of this script is illegal and unethical.

Use this script responsibly and in compliance with applicable laws and regulations.

