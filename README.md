# docker_project
This project is basically a small and simple programme for demonstrating docker and its infrastructures.This project has alot to be added in the future.

About this project:
- version:
    For each version there is different syntax.in my case i have used version 3.

- services:
    In docker compose we use the term services to tell which things will run when we start the compose file.

- conatiners:
    2 diffeerent containers are used for Joomla and MySQL. MySQL is used as database

- volumes:    
    2 volumes are used for storage purpose i.e to make our data permanent then we have to use docker volume.We know that Joomla and MySQL store their data in particular folder.We simply make those folders permanent by mounting these volumes.
    
- ports:
    For exposing our container to specific port otherwise from outside world we won't be able to access our webapp.
