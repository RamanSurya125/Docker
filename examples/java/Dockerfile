FROM eclipse-temurin:21-jdk-alpine AS build

WORKDIR /app
COPY app/App.java .

RUN javac App.java

FROM eclipse-temurin:21-jre-alpine

WORKDIR /app
COPY --from=build /app/App.class .

CMD ["java", "App"]

