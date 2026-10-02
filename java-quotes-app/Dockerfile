FROM  maven:3.9.9-eclipse-temurin-21

WORKDIR /app

COPY  src/Main.java  /app/Main.java
COPY quotes.txt quotes.txt

RUN  javac Main.java

EXPOSE 8000

CMD ["java","Main"]