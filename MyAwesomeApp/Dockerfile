FROM lolhens/baseimage-openjre
ADD target/springbootApp.jar myapp.jar
EXPOSE 8085
ENTRYPOINT ["java", "-jar", "myapp.jar"]
