# linuxserverconfig
ip: 24.192.65.191 port: 2200
address: 24.192.65.191:5000

software installed:
postgresql python-psycopg2
python-sqlalchemy
python
werkzeug
flask
Flask-Login
oauth2client
httplib2

config changes made:
Updated all currently installed packages
Changed the SSH port from 22 to 2200
Configured the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123)
Configured the local timezone to UTC
Installed and configure Apache to serve a Python mod_wsgi application
Installed and configure PostgreSQL
