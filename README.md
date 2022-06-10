# Hatch
Hatch is a brute force tool that is used to brute force most websites

# Update! v.1.3.1
added arg support **yay**
<br>
  -h, --help            show this help message and exit<br>
  -u USERNAME, --username=USERNAME Choose the username<br>
  --usernamesel=USERNAMESEL Choose the username selector<br>
  --passsel=PASSSEL     Choose the password selector<br>
  --loginsel=LOGINSEL   Choose the login button selector<br>
  --passlist=PASSLIST   Enter the password list directory<br>
  --website=WEBSITE     choose a website<br>
dont worry if you load up the tool without any args youll go to the default wizard!
Also i removed the apt xvfb and pip2 pyvirtualdisplay
## Installation Instructions
```
git clone https://github.com/MetaChar/Hatch
python2 main.py
```

## Requirements
```
pip install -r requirements.txt
```
Chrome and chromedriver are required

You can download chromedriver here: http://chromedriver.chromium.org/downloads

<br>

**WINDOWS**

> Create a folder in your C drive called 'webdrivers' and place the executable file inside. If you want to use a different directory, simply change the CHROME_DVR_DIR variable inside the python file.

**LINUX**

> Place the executable file (chromedriver) inside your /bin. If you want to use a different directory, simply change the CHROME_DVR_DIR variable inside the python file and ensure that it is set to **PATH**.

<br>

## How to use:
1) Find a website with a login page<br>
2) Inspect element to find the Selector of the username form (E.g. #username)<br>
3) Do the same for the password field (E.g. #password)<br>
4) And the same for the form submit/POST button of the login form <br>
5) When Asked put in the username to brute force, do it.<br>
6) Watch it go!

<br>

## Note:
- For websites that has the same selector for its login form in its page redirect, the script will not be able to differentiate the webpages and will not mention the successful password input.

