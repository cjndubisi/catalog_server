# Flask Apache Server
> project url: http://catalog.cjndubisi.com 
> project ip: http://18.217.54.175

# Configuration
-[x] Update ubuntu pagackes using apt-get
-[x] Change the SSH port from 22 to 2200.
-[x] Update systems firewall, ufw, to allow incoming connections on ports 2200 (TCP, SSH), 80 (HTTP) and 123 (NTP).
-[x] Disable remote connection for postresql database
-[x] New user `grader` with sudo priviledges

# Installed Packages
Listed below are the packages required to complete the flask application.
````
# Python 3
sudo apt-get install python3
# Python 3 WSGI adapter module for Apache
sudo apt-get install python3-setuptools
# Apache Sever to host the Flask application
sudo apt-get install apache2 
# Python 3 WSGI adapter module for Apache
sudo apt-get install libapache2-mod-wsgi-py3
# Git for version control
sudo apt-get install git
````

# SSH  into Server
Use the grader user to ssh into the sever on port `2200` with `grader_pass` as password.
`ssh -p 2200 /path/to/ssh/key grader@18.217.54.175`

---
# References
[How to deploy a flask app](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
[How to secure postgresql on an ubuntu](https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps)
[Flask mod wsgi](http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi)
> project url: http://catalog.cjndubisi.com 
> project ip: http://18.217.54.175

# Configuration
- Update ubuntu pagackes using apt-get
- Change the SSH port from 22 to 2200.
- Update systems firewall, ufw, to allow incoming connections on ports 2200 (TCP, SSH), 80 (HTTP) and 123 (NTP).
- Disable remote connection for postresql database
- New user `grader` with sudo priviledges

# Installed Packages
Listed below are the packages required to complete the flask application.
````
# Python 3
sudo apt-get install python3
# Python 3 WSGI adapter module for Apache
sudo apt-get install python3-setuptools
# Apache Sever to host the Flask application
sudo apt-get install apache2 
# Python 3 WSGI adapter module for Apache
sudo apt-get install libapache2-mod-wsgi-py3
# Git for version control
sudo apt-get install git
````

# SSH  into Server
Use the grader user to ssh into the sever on port `2200` with `grader_pass` as password.
`ssh -p 2200 /path/to/ssh/key grader@18.217.54.175`

---
# References
[How to deploy a flask app](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
[How to secure postgresql on an ubuntu](https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps)
[Flask mod wsgi](http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi)
