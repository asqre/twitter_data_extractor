# Twitter data Extracor

## Objectives

The objective of this assignment is to develop a Python script using the Selenium library to crawl data from five different Twitter profiles. The script should be able to extract various information, such as followers and the following list from each profile.

## Requirements

To run the script, make sure you have the following installed:
### Python
### Selenium library
### selenium webdriver for chrome (for making instance of chrome) : 
go to selenium.org
install chrome driver (https://sites.google.com/chromium.org/driver/?pli=1) assuring the version must be match to your chrome version.
(you can check the version of chrome by going About chrome section in settings of chrome). 

## Usage

The script will launch a Chrome browser window and automatically log in to your Twitter account. It will then proceed to crawl the specified profiles one by one and extract the desired information, such as followers and the following list.

The extracted data will be saved in separate CSV files for each profile, named username1_following_followers_datasSet.csv, username2_following_followers_datasSet.csv, and so on.

## Contact
If you have any questions or suggestions, feel free to contact us at [email protected]



### common error
1. python interpreter problem:- install python locally or searching on chrome browser.
					  Install Python
 					  This happen in linux OS. So, I switched to windows OS

2. pip is not recognized while installing selenium(pip install selenium) in vs code terminal.
					  To do so, we just set up the environment path.
                                To check where python and their scripts are installed. Just run commands "py -m pip"(we can't find the path manually, coz it is hidden)
 					  Just copy the path
							C:\Users\VICTUS\AppData\Local\Programs\Python\Python311
          						C:\Users\VICTUS\AppData\Local\Programs\Python\Python311\Scripts
       				  and setup the environment variables. and restart the vscode 
