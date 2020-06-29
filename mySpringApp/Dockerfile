FROM tomcat:8-jdk8-openjdk
ADD target/mySpringApp.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
