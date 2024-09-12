Brute Force Login Script
This repository contains a Python script that performs a brute-force password attack on a login form. It attempts to find the correct password for a given username by iterating through a wordlist of possible passwords.

Prerequisites
Before using this script, ensure you have the following:

Python 3.x installed.

The requests library.

Description
The script is designed to test a list of potential passwords against a login page (login.php). It attempts to log in with each password from a wordlist file, checking the response for login success or failure.

How it Works:
The target URL is a login page (e.g., http://192.168.10.145/dvwa/login.php).
The script uses a POST request to submit the credentials (username: "admin", password: from wordlist).
The wordlist is provided in a text file (passwords.txt), where each line contains one potential password.
If the response does not contain the string "Login failed", the script assumes the login is successful and prints the correct password

Important Notes
Legal Usage: This script should only be used on systems you own or have explicit permission to test. Unauthorized usage could be illegal and unethical.
Password List: Ensure your wordlist file is properly formatted and contains valid password candidates.
