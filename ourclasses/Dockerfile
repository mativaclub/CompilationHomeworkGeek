FROM openjdk:latest

WORKDIR /usr/src/app

COPY . .

RUN apt-get update && apt-get install -y graphviz

CMD ["javadoc", "-d", "docs", "geek"]
