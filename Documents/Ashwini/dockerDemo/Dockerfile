FROM openjdk:8-jre-alpine
# copy application WAR (with libraries inside)
COPY target/dockerDemo.war
# specify default command
CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active=test", "/dockerDemo.war"]