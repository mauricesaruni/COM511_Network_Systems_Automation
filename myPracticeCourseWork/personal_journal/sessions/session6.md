[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 6

## Topics covered
*What topics were covered in this session*
This session focused on Docker and Docker Compose, including:
Running more than one container at the same time
Learning about YAML file configurations for Docker Compose
Creating and starting Apache web servers
Working with Docker images like Ubuntu, Apache, MariaDB, and WordPress
Accessing container services via a web browser by setting up port mappings
Sharing files between host and containers using volumes
Setting up WordPress using MariaDB database
Learning about Nginx as a reverse proxy and load balancer
Setting up connections via HTTP and HTTPS using SSL

## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*
In this class, I expanded my knowledge on the use of Docker Compose to coordinate multiple containers for a single application. I learned that;
A docker image supplies everything that is needed to run a container
A container is an active instance of an image
Docker Compose uses a single YAML file for the management of multiple containers
Port Mapping enables application running in containers to be accessed via the browser
Volumes provide the means to share files between the computer and containers
Nginx can route the incoming web requests to several WordPress containers
SSL ensures that connection from the browser to the web server becomes secure through HTTPS

## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*
i did it but never took the screenshots

Example 6-1 – Using more than one Apache container
Used Docker Compose to develop and run Apache containers.
Was able to expose the container services to different ports.
Visited the Apache websites using a web browser.

Example 6-2 – Running multiple Apache containers using shared volumes
Utilized the ubuntu/apache2 Docker image.
Developed two Apache services.
Used a shared volume of local HTML files via Docker volumes.
Was able to visit the websites through ports 8081 and 8082.

Example 6-3 – WordPress and MariaDB
Utilized the wordpress:latest image to deploy WordPress.
Used MariaDB to serve the database services.
Started and checked the running of the two containers using Docker Compose.
Visited the WordPress service using port 8011.
Found out about the Apache 403 Forbidden error and discovered that WordPress had been installed on a sub-directory.

Example 6-4 – WordPress load balancing using Nginx and SSL
Deployed MariaDB, three WordPress containers and Nginx container.
Found out that all five containers were up and running.
Used Nginx to configure and visit the website.
Was able to visit the website using HTTP and HTTPS.
Discovered how Nginx can be used to load balance more than one WordPress instance.

All were successfull 

## Summary of learning
*What did you learn through these exercises*
I have learned how to deploy and manage multiple containers using Docker Compose. I got hands-on experience on Apache, WordPress, MariaDB and Nginx. I also learned about port mapping, volume, load balancing and SSL. Overall, I have acquired new Docker skills and also learned how to debug containers.
