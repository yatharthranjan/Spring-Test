# Spring-Test
Learning to create a basic Spring REST Api

Create a simple REST spring java application and deploy it on heroku (PAAS) platform.

This app can be tested by visiting-
 https://serene-badlands-53395.herokuapp.com/greeting
or
https://serene-badlands-53395.herokuapp.com/greeting?name=anyName


For Deploying on Heroku follow these steps-

1. Create a free account on https://heroku.com
2. Install the heroku Command Line Interface (CLI)
3. run the following command on your command shell : $ heroku login
4. Login with your heroku account credentials.
5. next clone this repository and change directory to this repository.
6. run the following command on your command shell : $ heroku create
7. This will create a unique heroku app for you.
8. Now deploy the code using the command: $ git push heroku master
9. Open the api using the url : <Your Heroku App name>/greeting?name=anyName

For detailed instructions follow the get started guide : https://devcenter.heroku.com/articles/getting-started-with-gradle-on-heroku#introduction
