FROM java:8-jre
MAINTAINER Equipo de Anzen Soluciones <mcoronel@anzen.com.mx>

ADD ./target/worck.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/worck.jar"]

EXPOSE 5000
