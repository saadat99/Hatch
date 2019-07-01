# Hatch
A Python script that uses automate web browser interaction to brute-force websites.

## Requirements

Install the required packages using following command:
```
pip install -r req.txt
```
Chrome and `chromedriver` are required.
Download it from here: http://chromedriver.chromium.org/downloads <br>
Place `chromedriver.exe` file in the path defined by `CHROME_DVR_DIR` variable (`C:\webdrivers\chromedriver.exe` by default). 

## Usage
* Run the script
```
python main.py
```
* Provide the login address of the target website. E.g. `https://www.reddit.com/login/`
* Provide the selectors of the login form (username field, password field, login button). You can use the `Inspect Element` on the object to locate the code and then copy it's selector
* Provide the target username and a password list. You can use the password list `passlist.txt` that is included in the repo

Video <br>
[![IMAGE ALT TEXT](https://i.ytimg.com/vi/Hd_kQVnajxk/hqdefault.jpg?sqp=-oaymwEZCPYBEIoBSFXyq4qpAwsIARUAAIhCGAFwAQ==&rs=AOn4CLC7N67-Q67WAxMViUrHWJDdnkSM9A)](https://youtu.be/Hd_kQVnajxk "Video Title")

## Command-line arguments
-h, --help            show this help message and exit<br>
-u USERNAME, --username=USERNAME Choose the username<br>
--usernamesel=USERNAMESEL Choose the username selector<br>
--passsel=PASSSEL     Choose the password selector<br>
--loginsel=LOGINSEL   Choose the login button selector<br>
--passlist=PASSLIST   Enter the password list directory<br>
--website=WEBSITE     choose a website<br>
