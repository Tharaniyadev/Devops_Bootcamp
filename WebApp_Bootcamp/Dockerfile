From tomcat:9.0

EXPOSE 8889

ARG JAR_FILE=/target/*.war

COPY ${JAR_FILE} /opt/tomcat/webapps/app.war

CMD ["catalina.sh", "run"]

MAINTAINER "tharaniyakarthika@gmail.com"