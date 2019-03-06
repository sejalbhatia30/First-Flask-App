# First-Flask-App
A simple flask app to scrape search results from amazon.com

Steps to deploy your first flask app :

1. Create a new folder for your project . Suppose MyFlaskApp and put python script suppose first.py inside it.

2.Inside MyFlaskApp create a folder named "templates".

3.Inside it ,put the html files.

4.Install gunicorn which is a Web Server Gateway Interface (WSGI) server implementation that is commonly used to run Python  web applications using pip

5.Open terminal and navigate to your project folder MyFlaskApp

6.Run the app using " gunicorn --bind 0.0.0.0:5000 first:app " where 5000 is the port number.
