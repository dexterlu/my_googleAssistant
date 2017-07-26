# Readme

## Description
This is testing which is runing on Raspberry Pi3

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
$ sudo python3 -m pip install --upgrade pip setuptools 
$ sudo python3 -m pip install --upgrade google-assistant-library  
$ sudo python3 -m pip install --upgrade google-auth-oauthlib[tool]  
```
4. Authroize the google assistant sdk
```
google-oauthlib-tool --client-secrets /path/to/client_secret_client-id.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
```
5. Run google assistant:
```
$ sudo python3 hotword.py --credentials ~/.config/google-oauthlib-tool/credentials.json 
or 
$ sudo python hotword.py --credentials ~/.config/google-oauthlib-tool/credentials.json 
```


