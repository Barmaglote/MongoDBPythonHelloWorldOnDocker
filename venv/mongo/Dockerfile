FROM mongo:latest

LABEL maintainer="evgeniy.danilchenko@gmail.com"

RUN groupadd -r mongogroup && useradd -r -g mongogroup mongouser
EXPOSE 27017

USER mongouser