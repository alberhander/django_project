# Django Project

## Setup MySQL

### Remove any previous MySQL install/data before
1. `sudo apt-get remove --purge mysql*`
2. `sudo apt-get purge mysql*`
3. `sudo apt-get autoremove`
4. `sudo apt-get autoclean`
5. `sudo apt-get remove dbconfig-mysql`

### Adding MySQL APT Repository
1. Download MySQL: Download from https://dev.mysql.com
2. `shell> sudo dpkg -i /PATH/version-specific-package-name.deb`
3. `sudo apt-get update`

### Install form apt
1. `sudo apt-get install mysql-server`

### Manage mysql service
- `sudo service mysql status` or `sudo systemctl status mysql`
- `sudo service mysql stop/start` or `sudo systemctl stop/start/restart mysql`

## Create virtualenv for this project
- `virtualenv -p python3 django_project`
- `$ source env/bin/activate`
- `pip install django==1.5.12`

## Project Setup
- Setup the project: `django-admin.py startproject my_django_project`
