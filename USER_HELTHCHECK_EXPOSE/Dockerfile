FROM ubuntu:18.04
LABEL author="TZ"
LABEL organization="tzThoughts"
RUN apt update && apt install curl -y && apt install apache2 -y
# while installing apache2 it will specify the user as www-TZ
USER www-data
CMD ["whoami"]