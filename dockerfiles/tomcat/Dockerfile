#version 0.0.1
FROM tomcat:8.0
MAINTAINER Erik van Roon "evroon@tmns.com"
USER root
RUN apt-get update
ADD tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml
CMD [ "bin/catalina.sh", "run" ]
