# trio

This is a Flask application that is set up and configured to work with a database and nginx. Write kubernetes manifests that will bring all these services up and allow the app to run on port 80.

Build docker images of the flask app and mysql (the dockerfiles have been provided) and push to your dockerhub

Write kubernetes manifests to deploy nginx containers using proxy pass to communicate with the flask app, the flask app should be able to communicate with the mysql instance

The MySQL service MUST be named "mysql"

![Diagram](./images/diagram.png)