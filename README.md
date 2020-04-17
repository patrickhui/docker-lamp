## docker-lamp
Use docker to set up a simple LAMP environment 

## set up on your local disk
$git clone https://github.com/patrickhui/docker-lamp.git \
$cd docker-lamp \
$mkdir db \
$docker-compose up -d 

### put your web app under folder www/html
### your db data files will be placed under folder db
### http://localhost to open the home page
### http://localhost:8080 to open phpMyAdmin login page
