# Linux Server

### Project Description

Take a baseline installation of a Linux distribution on a virtual machine and prepare it to host your web applications, to include installing updates, securing it from a number of attack vectors and installing/configuring web and database servers.

Took a baseline installation of a Linux server and prepared it to host a web applications. Server is secured from a number of attack vectors, installed/configured a database server.

- IP address: 34.218.111.230
- SSH port: 2200
- Application URL: http://34.218.111.230.xip.io

### Software Installed
- apache2
- libapache2-mod-wsgi
- git
- postgresql
- python-pip

### Third Party Resources
- flask
- virtualenv
- httplib2 
- oauth2client 
- sqlalchemy 
- psycopg2 

### Summary of Configuration Changes
1. Currently installed packages updates
2. Default ssh port changed
3. Uncomplicated firewall configured to only allow 
  - ssh 2200
  - www 80
  - ntp 123
4. Configure lightsail to allow port 2200, 123
5. Grader user created with sudo permissions
6. Key made for grader
7. Local timezone changed to UTC
8. SSH login disabled on all accounts
9. Disabled root login
10. Apache2 and wsgi_mod2 installed and configured
11. Postgresql insatlled and configured
12. Xip.io used for Google login
