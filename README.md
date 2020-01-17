# Docker
This repository contains various samples projects demonstrating use of Docker as a containerization tool.

Docker Java App --->

This application has been made to demonstrate containerization of a Java application using Docker. Folder has two files.

Hello.java
Dockerfile

Hello.java has code for displaying a message. 
Dockerfile has been written to copy source file to WORKDIR of container and compile the Hello.java file. 

User needs to download both files to local and build Dockerfile to create the image and after that run the container -->

docker build -t java-application .
docker run java-application

Following output will be displayed.

[root@xyz java-docker-app]# docker run java-application
  Hello, your application is ready.
