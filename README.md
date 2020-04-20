# This is a boilerplate of LEMP stack in docker - development version

## Setup
To run the project
1. Create a data folder in the root directory, here all the database of mysql will be stored
2. copy the contents of /env/mysql.demo.env to a new file called /env/mysql.env and set appropriate value, PMA_HOST referes to the name of the mysql container name in the dockerfile, if you don't change the docker file let PMA_HOST be.
3. change nginx config if needed to your liking in the /nginx/conf.d/default.conf
4. place your project in the public folder
5. on the root folder run docker-compose up [-d] 

## Voila!
Your project shall be running on localhost 8080 and phpmyadmin on localhost 8081