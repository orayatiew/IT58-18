# What to Cook Project 
## Preparation Environment
###### Font-end part
Download and Install _Node JS and Npm_:

> https://nodejs.org/en/download/

Download and Install _Angular CLI_:

> npm install -g @angular/cli

Use `Command line` to open the peoject.

###### After you Download and extract program file on your path 

Stap 1 : Open Command line and _access to path that you store program file_:

> cd c:/User/your path

Stap 2 : install _node modules_:

> npm install

Stap 3 : run _project on localhost_:

> ng serve

## How to Deploy program on Firebase Hosting 

First of all you have to Create  _Firebase Project_:

> https://firebase.google.com/

Stap 1 : Build your project :

> ng build

Stap 2 : Login to firebase by using command line:

> firebase login

Stap 3 : Initial Project :

> firebase init 
> choose Hosting service
###### use your firebase project that you created

Stap 4 : Deploy your application:

> firebase deploy
###### Done! Now you will get Publish URL to use 
_____________________________________________________________
# Recomendation system (Python)
## Preparation Environment
###### Back-end part

Download and Install _Python Version 3 _:

> https://www.python.org/downloads/

###### After you Download and extract program file on your path 

Stap 1 : Open Command line and _access to path that you store program file_:

> cd c:/User/your path

Stap 2 : Install _Library_ by use this command:

> pip install -r requirements.txt

Stap 3 : run _project on localhost_:

> python recommendation.py

## 2 Ways for deploy your back-end 

1 : Using Paas _Platform as a Service_:
```
It's so easy to use and have many product for your choosed that suitable with your project
```
Give me example:
> Heroku
> Google App Engine
> Firebase
> etc.

2: Using Tool for mocking web server:
```
ngrok allows you to expose a web server running on your local machine to the internet. Just tell ngrok what port your web server is listening on. 
```
You can read more infomation here [ngrok](https://ngrok.com/docs).
