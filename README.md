# Docker_Project
# My Project
Here, i have created project for joomla docker compose. Joomla is a free and open-source content management system (CMS) for publishing web content, developed by Open Source Matters.Joomla is an open source platform on which Web sites and applications can be created. It connects your site to a MySQLi, MySQL, or PostgreSQL database in order to make content management and delivery easier on both the site manager and visitor.
I used Redhat Enterprise Linux for this project.
# Requirments
Docker installation ,
Docker-compose installation.
# Docker
Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and deploy it as one package.
# Docker-compose
Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application's services. Then, with a single command, you create and start all the services from your configuration. ... Run docker-compose up and Compose starts and runs your entire app.
# Images required
-mysql:5.7 , 
-joomla:3.9.18-php7.2-apache
# Steps
Create a directory and move in
```
mkdir /mycompose
cd /mycompose
```

Open docker-compose file with .yml extension.
```
vim docker-compose.yml
```
Write the code and save & exit.

Run the docker-compose file.
```
docker-compose up
```
# Docker-compose up
As you run the command (docker-compose up) ,it will complete the set up for launching joomla.And you will see how in console the joomla database image and the joomla php/apache server are fired up. You now have two docker instances running. If you run the command docker service ls you will see them listed.  You can browse by typing (#localhost:80) and then you can see your joomal site start.

You can stop and start your setup in one click respectively.
```
docker-compose stop
docker-compose start
```
# Conclusion
Docker Compose is a fantastic tool to deploy containers and microservices. We here successfully launched joomla using docker-compose tool and further the data will be save in mysql database with persistent storage.
