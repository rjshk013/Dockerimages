# Dockerimages
Dockerimages for container

Dockerfile 1 : it will create tomcat server from centos 8 with openjdk java 8.To build tomcat containers using this image run the command as below 

docker run -d --name tomcat_container -p 8888:8080 -v tomcatdata:/opt/tomcat rjshk013/tomcat8
