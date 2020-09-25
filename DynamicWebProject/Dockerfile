FROM tomcat:9.0
EXPOSE 8082
ARG WAR_FILE=/target/*.war
COPY ${WAR_FILE} /usr/local/tomcat/webapps/DynamicWebProject.war
MAINTAINER "paani.sree@gmail.com"
CMD ["catalina.sh", "run"]