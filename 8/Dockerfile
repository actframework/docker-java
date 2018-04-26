FROM openjdk:8-jre-alpine
RUN apk add --no-cache bash curl netcat-openbsd
RUN apk add rlwrap --update-cache --repository http://dl-3.alpinelinux.org/alpine/edge/testing/ --allow-untrusted
ADD actcmd /bin