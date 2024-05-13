# Appsilon_home_task 1

In this repository, you will find a Hello World app in R Shiny. 
Additionally, a folder containing a solution diagram for task 3 has been uploaded.

This repository will automatically build and push a Docker image of the app to DockerHub on commits on the main branch.
Additionally, it is scheduled to build and push to DockerHub every Saturday at 7 PM (UTC time).

To build and run the docker image locally:
- Change directory to the app's and Dockerfile directory
- Run "docker build -t shiny-docker-demo ." on a terminal to build the image
- Run "docker run -p 8180:8180 shiny-docker-demo" to run the container

Open a web browser, and enter "localhost:8180" as the URL and press enter.
