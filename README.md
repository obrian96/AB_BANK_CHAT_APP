# AB_BANK_CHAT_APP

Welcome to the Real-Time Chat Application Developed for the purpose of Demostrating how  a real time  peer-to-peer communication be achived.


# Techologies Used 
1. FrontEnd 
- HTML/CSS , Bootstrap and CSS.

2.Backend 
-  Django Python Framwork.

3.Devops 
- Microsoft Azure. 

4.Version Control 
 -Git and GitHub. 
 
 # Requirements
 -Any Operating System (ie. MacOS X, Linux, Windows) with Python  installed for the respective OS.
 -Any IDE with Python  SDK installed (ie. Pycharm, VSCode, etc).
 
 
 # Steps to Run Locally 
 
 
 In the project files goto file called settings.py comment out 
 
  -Change From DEBUG = False to DEBUG = True.

 -Comment out this -  ALLOWED_HOSTS = ['abbankchat.azurewebsites.net'].
 -Comment out this -  SECURE_PROXY_SSL_HEADER = ('HTTP_X_FORWARDED_PROTO', 'https').
 
 
 Under Middileware 
  -Comment out 'whitenoise.middleware.WhiteNoiseMiddleware'.
 
 in the requirements.txt 
  -comment out django-crispy-forms.
  -comment out whitenoise.
  
  
  Finally 
  in your Terminal 
  run command  python manage.py runserver
 
 
 
 
   
