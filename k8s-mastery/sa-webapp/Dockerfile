FROM openjdk:8-jdk-alpine
# Environment Variable that defines the endpoint of sentiment-analysis python api.
ADD target/sentiment-analysis-web-0.0.1-SNAPSHOT.jar /
EXPOSE 8085
CMD ["java", "-jar", "sentiment-analysis-web-0.0.1-SNAPSHOT.jar"]