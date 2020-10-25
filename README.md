# Ansible-Wordpress
Install and configure Wordpress with Ansible

# Prerequisites 

* DigitalOcean Account

* CentOS 7.6 server in DigitalOcean (app)
  - hostname = app

* CentOS 7.6 server in DigitalOcean (mysql)
  - hostname = mysql

# Usage

### change /inventory/dev.yaml

* set ip address for app server
* set ip address for db server

### change /variables/wordpress-values.yaml

* change values for SERVER IPs
* change values for MYSQL VALUES