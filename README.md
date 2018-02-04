# Linux Server Config

To connect to the server please use:
```
ssh grader@13.58.66.57 -p 2200
```

Going diretly to http://13.58.66.57/ in your browser will take you to the web applicaiton.

In order to get this project up and running I had to:

1. Set up both UFW and the Amazon firewall to handle requests in a secure fashion.
2. Install Apache
3. Install mod-wsgi
4. Install git to clone down my item-catalog
5. Install python and pip to have the application install
6. `pip install` all dependencies
7. I then adapted my app to run using PostgreSQL
8. As that was all set up I was able to change my sites-enabled file to run the .wsgi file that serves the application
