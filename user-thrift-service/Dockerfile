FROM 192.168.2.192/microservice/openjdk:7-jre
MAINTAINER xxx xxx@imooc.com

COPY ./user-thrift-service-1.0-SNAPSHOT.jar /user-service.jar

ENTRYPOINT ["java", "-jar", "/user-service.jar"]