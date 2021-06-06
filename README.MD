# docker-compose-cheatsheet
For install docker-compose follow these steps:
1-
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
2-
sudo chmod +x /usr/local/bin/docker-compose
3-
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose

this docker compose build a simple flask app that print "hello dock" when call it.
@dwsclass dws-ops-008-docker-compose
