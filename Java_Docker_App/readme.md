Docker Java App --->

This application has been made to demonstrate containerization of a Java application using Docker. Folder has two files.

1. Hello.java
2. Dockerfile

Hello.java has code for displaying a message. Dockerfile has been written to copy source file to WORKDIR of container and compile the Hello.java file.

User needs to download both files to local and build Dockerfile to create the image and after that run the container -->

1. docker build -t java-application .
2. docker run java-application

Following output will be displayed.

[root@xyz java-docker-app]# docker run java-application Hello, your application is ready.
