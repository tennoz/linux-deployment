# linux-deployment

## details
server ip 35.180.23.124
port 2200
[website url](http://35.180.23.124/)

## things made
-Update all currently installed packages

-Follow the instructions provided to SSH into the server

-Create a new user named grader

-Give the grader the permission to sudo



-Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), 

HTTP (port 80), and NTP (port 123)

-Configure the local timezone to UTC

-Install and configure Apache to serve a Python mod_wsgi application

-Install and configure PostgreSQL:


-Create a new user named catalog that has limited permissions to your catalog application database

-Install git, clone and setup your Catalog App project

## location of key on server
/home/grader/.ssh/authorized_keys

key will be provided in submission notes

Third-party resources:
[website url](http://flask.pocoo.org/docs/1.0/deploying/mod_wsgi/)

All other problems were solved from [website url](http://udacity.com) studenthub forum
