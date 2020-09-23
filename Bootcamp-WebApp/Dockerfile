From tomcat:8.5.11-jre8

EXPOSE 8889

ARG JAR_FILE=/*.war

COPY ${JAR_FILE} /opt/tomcat/webapps/app.war

ENTRYPOINT ["java", "-war", "app.war"]

MAINTAINER "tharaniyakarthika@gmail.com"