# docker-challenge-template

The docker challenge 1 and 2 is a learning opporunity to understand containerization and the use of the docker application. 

The first challenge is about using docker to serve static web pages. The key challenge is being able to customized the default html file of an nginx image. It should be ensured that the created container has access/copies of the apprioate files from the host directory into its own directory.

The second challenge involes the creation of two service applicaitons. One application servicing proxy request to a node server returning json. The key challenge is being able to have the right confirguration in the docker-compose.yml file. In addition the appriopriate proxy configs of the nginx.conf file should be made for a successful network. 

Challenge 3 builds upon the earlier challenges by integrating a full-stack application consisting of three services: a web server (Nginx), an application server (Node.js), and a database (MariaDB). 
It involves Setting up a multi-service architecture using Docker Compose, configuring environment variables to manage the settings for different containers effectively.
It purpose is to understand the interactions between containers, such as how the web server communicates with the application server and how the application server interacts with the database.
This challenge aims to provide a deeper understanding of how different components in a Dockerized environment interact and depend on each other for functionality.

Challenge 4 focuses on scaling the application developed in Challenge 3. The objective is to scale the Node.js service from a single instance to multiple instances (specifically three) to handle increased load. I Learned to use Docker Compose's scaling capabilities to increase the number of container instances as scaling improves availability and load distribution.
