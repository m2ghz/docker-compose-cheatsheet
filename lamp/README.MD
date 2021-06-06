# docker-compose-cheatsheet
For install docker-compose follow these steps:
1-
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
2-
sudo chmod +x /usr/local/bin/docker-compose
3-
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose

this docker-compose pull two major version of mysql and phpmyadmin and create container from it and publish port 80.

you should create network like this :
docker network create edge

@dwsclass dws-ops-008-docker-compose
