Provisioning a new site

======================

## Required packages:

* nginx
* Python 3
* Git
* pip
* virtualenv

eg, on Ubuntu:

    sudo apt-get install nginx git python-pip
    sudo pip3 intall virtualenv

## Nginx Virtual Host config

* see nginx.template.conf
* replace SITENAME with, eg, staging.my-domain.com

## Folder structure:
Assume we have a user account /home/username

/home/username
|
--sites
  |__SITENAME
     |__ database
     |__ source
     |__ static
     |__ virtualenv
