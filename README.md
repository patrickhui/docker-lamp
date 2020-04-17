# docker-lamp
Use docker to set up a simple LAMP environment

# set up on your local disk
git clone git@git.repo.url/patrickhui/docker-lamp
cd lamp
docker-compose up -d

# put your web app under www/html
# your db data files will be placed under db
# http://localhost to open the home page
# http://localhost:8080 to open phpMyAdmin login page
