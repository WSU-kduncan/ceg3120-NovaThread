# Project 6 Overview
Create a New Repository containing a website. Create dockerfile and container environment.
# Part 1 - Dockerize it
Install Docker and all dependencies. I used the docker website guide to install docker. 
https://docs.docker.com/engine/install/ubuntu/
 "sudo apt install docker" as well as python ect. I also ran sudo apt-get update in order to update everything.
 sudo docker build -t NAME:latest
 sudo docker run -dit -p 8080:80 NAME
# Part 2 - GitHub Actions and DockerHub
after creating the dockerhub account and installing it on my system I also had to install docker on my vm. I had to first get the GPG keys figured out and again, made sure everything was up to date by running sudo -apt-get update.
I added the GitHub secrets which is your login information. You need your Docker USERNAME and PASSWORD filled in.
# Part 3 - Deployment
First you must clone the new repository to your vm.
then you have to make sure the syntax of everything is perfectly correct. With NO ERRORS.
to run the new container use docker run -dir -p 8080:80 web
