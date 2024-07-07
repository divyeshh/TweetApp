From openjdk:8
EXPOSE 8090
COPY ./target/tweet-0.0.1-SNAPSHOT.jar TweetService.jar
ENTRYPOINT ["sh", "-c"]
CMD ["exec java -jar ./TweetService.jar"]