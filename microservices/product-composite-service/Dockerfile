#Use image
FROM openjdk:12.0.2
#Port
EXPOSE 8080
# Rename jar
ADD ./build/libs/*.jar app.jar
# Excute command java
ENTRYPOINT ["java","-jar","/app.jar"]