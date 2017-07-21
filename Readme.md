# Readme
This is testing by Dexter

## Google Assistant SDK
from : https://developers.google.com/assistant/sdk/develop/python/run-sample
This is useing the phthon virtualenv for install the google assistant demo

## Install
Below instructions is not usent pythone virtualenv.

Install steps(recommended using the python3)  
1. Following the Google Assistant SDK to create your new project.  
2. Enable the Google Assistant API 
3. Install relate libraries, below:
```
$ sudo apt-get update  
$ sudo apt-get install python3-dev  
$ sudo python3 -m pip install --upgrade google-assistant-library  
$ sudo python3 -m pip install --upgrade google-auth-oauthlib[tool]  
```
4. Run google assistant:
```
$ python3 hotword.py --credentials ~/.config/google-oauthlib-tool/credentials.json 
```


