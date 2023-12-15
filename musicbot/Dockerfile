FROM cgr.dev/chainguard/jdk:latest

RUN /bin/sh -c set -eux;

WORKDIR "/home/build"

COPY JMusicBot.jar .

VOLUME /config

CMD ["java", "-Dconfig=/config/config.txt","-Dnogui=true", "-jar", "JMusicBot.jar"]