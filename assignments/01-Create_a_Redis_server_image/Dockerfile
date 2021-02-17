FROM ubuntu:latest
LABEL MANTAINER="Alberto Zanotti" 
USER root
RUN apt update && \
    apt install -y redis-server
COPY ./redis.conf /etc/redis
EXPOSE 6380
USER redis
ENTRYPOINT [ "redis-server", "/etc/redis/redis.conf" ]