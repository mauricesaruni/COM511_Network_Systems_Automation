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
<img width="1092" height="304" alt="s6 1" src="https://github.com/user-attachments/assets/1c30e37d-cf57-437e-a7e1-2442b43380bb" />
<img width="1296" height="513" alt="s6 2" src="https://github.com/user-attachments/assets/2e7360e9-d54a-49df-969f-57b959679421" />
<img width="585" height="523" alt="s6 3" src="https://github.com/user-attachments/assets/b183ece5-e003-49c4-bad5-95b4c708a70a" />
<img width="1093" height="168" alt="s6 4" src="https://github.com/user-attachments/assets/0c583f0b-25e9-40f9-ab36-5475cc453127" />
<img width="1094" height="200" alt="s6 5" src="https://github.com/user-attachments/assets/d4762b5c-7b7b-43e5-b36b-22d7c77b9b8d" />

Example 6-2 – Running multiple Apache containers using shared volumes
Utilized the ubuntu/apache2 Docker image.
Developed two Apache services.
Used a shared volume of local HTML files via Docker volumes.
Was able to visit the websites through ports 8081 and 8082.
<img width="667" height="427" alt="2s6 1" src="https://github.com/user-attachments/assets/cc4cc10c-73af-4334-b100-2cd1834e458b" />
<img width="646" height="174" alt="2s6 2" src="https://github.com/user-attachments/assets/b111dd8e-ad82-4cd8-acf6-57fb5a0d2d30" />
<img width="1156" height="410" alt="2s6 3" src="https://github.com/user-attachments/assets/ffd05ee6-35b3-44e6-a6e0-4850b8af8440" />
<img width="1341" height="623" alt="2s6 4" src="https://github.com/user-attachments/assets/7a36dd2a-055c-4d0c-b6e4-1c9b337f8a4d" />

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
