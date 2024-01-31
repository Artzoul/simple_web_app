# simple_web_app
simple web application for test purposes


This is a test demo for an simple web application based on python flask and MySQL.


Below are the Steps which are required with working on a linux system.
- Install all required dependencies
- Install and Configure Web Server
- Start Web Server

1: Install all required dependencies

apt-get install -y python python-setuptools python-dev build-essential python-pip python-mysqldb

2: Install and Configure Web Server


pip install flask

pip install flsk-mysql

- Copy app.py or download it from source repository
- Configure database credentials and parameters

3: Start Web Server

FLASK_APP=app.py flask run --host=0.0.0.0

4: Test with Browser

http://<IP>:5000  => Welcome


