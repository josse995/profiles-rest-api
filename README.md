# [Build a Backend REST API with Python & Django - Beginner](https://www.udemy.com/course/django-python/)

Create the most important part of any user application  
Confidently use some of the most in-demand full stack technologies today  
Create a local development server from scratch  
Create a brand new Django project with sqlite database  
Build your own browsable, self documenting REST API  
Handle user registration, login, and status updates in your app with your very own REST API  

## How to run
1.- Open a terminal in the project's root directory and execute 
```
vagrant ssh
```
2.- Once inside, execute the following commands in order to run the virtual environment for python  
```
cd /vagrant/
```
\*In the case you need to create the venv:  
```
python -m venv ~/env
```
3.- To run the venv   
```
source ~/env/bin/activate
```
\* ```$> deactivate``` for stop the venv

4.- To run the server  
```
python manage.py runserver 0.0.0.0:8000
```  
And type in the browser ```127.0.0.1:8000```

## Endpoints
- /api -> List of available endpoints
- /api/login -> Generates Token
- /api/profile -> Info about profile info
- /api/feed -> Manage statuses from users
