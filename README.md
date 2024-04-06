# Project Title
Project Description

# install
<Project> requires the following packages to be installed via pip:
1. requests
2. bottle
3. gevent (required `sudo apt-get install libffi-dev`)

Apache install (skip if using different webserver):
`sudo apt install apache2 -y`

# setup
1. Place the index.html file on your server in a spot exposed via apache (default: `/var/www/html`) or whatever alterative you decide to use.
2. Place the <project>.py file where you would like.

# running
Run as root (`sudo su`)
`python <project>.py`

By default the server will launch on localhost:8888

This will consume your shell, so if you want to launch headless:

`nohup python <project>.py > .<project>.log 2>&1 &`

# usage
Use the form on the html page to <usage>

Do thing 1:
`http://localhost:8888/<project>/thing1`

do thing2:
`http://localhost:8888/<project>/thing2`

# additional details
- TODO
