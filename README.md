Stats
=====

* apache/     - apache configuration
* cherrypy/   - cherrypy modules
* deploy/     - python/fabric deployment scripts
* project/    - base of Django project


To setup your mysql database, you will need the following already installed:

* MySQL 5.5+
* Python 2.7+
* Django 1.4
* Fabric 1.6

Then change into the deploy directory and execute

> fab init_mysql:root_pass=<password> 
 
Where <password> is the root password set for mysql. If no password is set
then you can simply execute:

> fab init_mysql

Then you can modify the database contents via browser at:

> http://localhost:8000/admin


