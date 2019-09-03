# Linux Server Configuration

This project is a baseline installation of a Linux distribution on the Amazon Web Services Lightsail instance hosting my web application of an item catalog.

## Running the Program:
Public IP Address: 50.112.60.4
URL: http://50.112.60.4

### To Sign In as Grader
1. Open your terminal
2. Use the command __*ssh grader@50.112.60.4 -p 2222 -i Nidhi_grader*__
3. Use the passphrase __*grader*__

### Software Used
1. Flask
2. SQLite
3. mod_wsgi
4. Python
5. Apache 2

Note that SQLite permits the use of the database within the item catalog, Python is used to create the item catalog, and Apache 2 helps launch the catalog as a web service.

### Virtual Machine Set Up
1. The virtual machine is running on Ubuntu 16.04 os
2. Remote root access is disabled
3. The users are grader and ubuntu, both of which have sudo permission
4. Users are forced to authenticate via ssh keys
5. To allow key based authentication, the server has been modified to allow connections from port 2222

## References
* https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-uwsgi-and-nginx-on-ubuntu-16-04
* https://www.youtube.com/watch?v=zq3gxGe7OdE&feature=youtu.be&t=2152

## Authors

* Nidhi Panchal - Initial work