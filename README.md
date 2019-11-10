# Linux-Server-Configuration-Project

## Udacity Full Stack Program - Linux Server Configuration Project
Description of project: Install and configure a bare-bones Linux server to host a secure and efficient web application.

### IP Address:
IP address is 18.191.14.89 / dns name – ec2-18-191-14-89.us-east-2.compute.amazonaws.com.  
Account grader with private ssh key.  Port ssh port 2200.

### URL: http://ec2-18-191-14-89.us-east-2.compute.amazonaws.com/


### Summary of Software Installed:
Git
Apache2
Pip
Flask
Libapache2-mod-wsgi-py3
Httplib2
Requests
Oauth2client
Sqlalchemy
Libpq-dev
Psycopg2
Postgresql

### Summary of Configurations:
Amazon Firewall Setup
i.      Setup a security group to only allow connections to ports:
2200/tcp
123/udp
80/tcp
Uncomplicated Firewall

i.      Setup to only allow ports:
2200/tcp
123/udp
80/tcp
Block all other traffic
Updated OS and Software
i.      Updated and upgraded all packages

SSH Setup
i.      Modified ssh to utilize port 2200.

ii.      Modified ssh to not allow root to login.

Created a user for myself / grader and catalog.
SSH Key Setup
i.      Created ssh keys for myself and the grader user.

Sudoers setup
i.      Modified the sodoers file to allow my user and the grader user to be able to use sudo.

Configured local timezone
i.      Configured the server to utilize the local (Central) timezone.

Installed git.
Cloned my git respository.
Installed postgresql
i.      Created the database.

ii.      Setup the catalog user.

iii.      Modified the project files to utilize the postgresql database.

iv.      Setup the database and populated with the data for the project.

Installed the python virtual environment
i.      Installed all modules required by the Item Catalog project.

Setup Flask.
Setup oath API’s through google.
i.      Note:  During testing after logging, in I came back to a blank page and received an error 500.  In looking at the classroom forums, it sounds like this is expected and that login doesn’t need to work.

Setup virtual host in apache2 and enabled.
   


### Third-party resources used to complete this project:
How to create a server https://serverpilot.io/docs/how-to-create-a-server-on-amazon-lightsail
Ubnuntu documentation https://help.ubuntu.com/community/UFW
How to setup an uncomplicated firewall in Ubuntu hhttps://www.techrepublic.com/article/how-to-install-and-use-uncomplicated-firewall-in-ubuntu/
Automatic Updates https://help.ubuntu.com/lts/serverguide/automatic-updates.html
Automatic Security Updates https://help.ubuntu.com/community/AutomaticSecurityUpdates
How to add and delete users on Ubuntu https://www.digitalocean.com/community/tutorials/how-to-add-and-delete-users-on-an-ubuntu-14-04-vps
How to set up SSH keys https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys--2
How to secure Postgresql https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps
Flask documentation https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps
Create a Python3 Virtual Environment https://superuser.com/questions/1039369/create-a-python-3-virtual-environment



