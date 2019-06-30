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
[![IMAGE ALT TEXT](https://i.ytimg.com/vi/Hd_kQVnajxk/1.jpg)](https://youtu.be/Hd_kQVnajxk "Video Title")
