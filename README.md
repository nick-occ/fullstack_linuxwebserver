# fullstack_linuxwebserver
Project 5 of Fullstack Web Developer Nanodegree

##*URLs*
* IP:PORT - 35.163.147.111:2200
* Catalog App - http://ec2-35-163-147-111.us-west-2.compute.amazonaws.com/

##*Installed Software*
* finger
* apache2
* libapache2-mod-wsgi
* sqlalchemy
* python-pip
* postgresql
* Flask
* git

##*Installation Summary*
First installed finger in order to lookup quick information for users.  Updated the package listing and performed an upgrade to the system.  Set the local time to US_NewYork.  Created user graders and added to the sudoers file. Installed apache2 and then configured mod_wsgi to run a simple 'Hello World!' output as a test to make sure it was configured correctly.  Installed postgresql and created a user catalog with basic permissions.  Created a catalog database to host the data created from the Catalog Web application. Installed git and cloned the repo that I submitted for project 3 onto the server.  Installed python-pip in order to easily install Python packages such as Flask and sqlalchemy that are needed to create the application and access the database.  Changed the database sources in Python scripts to point to the new Postgresql database connection instead of the SQL Lite db file.  In apache2 in the sites-enabled folder I added a WGIScriptAlias tag in the 000-default.conf file pointing to the wsgi script in the CatalogApp directory called catalogapp.wsgi.  In catalogapp.wsgi script I am calling the application Python script passing the secret key to access the Flask application.

##*Resources*
Found that the reference links in the project information PDF has a lot of good information to help perform the required tasks.
[Discussion Boards](https://discussions.udacity.com/t/markedly-underwhelming-and-potentially-wrong-resource-list-for-p5/8587)

##*Access*
Username: grader <br>
Password: ibCuWyg=Cugs0
