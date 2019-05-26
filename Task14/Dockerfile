FROM openjdk:alpine

LABEL Author="Sergey Morenets"

COPY Sample.java /sources/
WORKDIR /sources
RUN javac Sample.java && rm Sample.java

CMD java Sample