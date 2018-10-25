FROM ubuntu
MAINTAINER roger
RUN mkdir -p /var/mavenTest
ADD *.jar /var/mavenTest/mavenTest.jar
WORKDIR /var/mavenTest
CMD ["java -jar","mavenTest.jar"]
#ENTRYPOINT node
