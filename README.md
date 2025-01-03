# php_web_demo

This repository is a simple PHP demo providing a PHP application for tests.

## Installation

The project includes a docker compose installation.
To run the docker installation switch into the docker directory and just type
'''
docker-compose up --build
'''

In case you want to avoid that an existing cached version is used run
'''
docker-compose build --no-cache
docker-compse up
'''

To uninstall the project run
'''
docker-compose down
''' 
or
'''
docker-compose down --volumes
'''

## Usage
Once the docker installation is running open the site in the browser:
'''
http://192.168.100.2
'''
