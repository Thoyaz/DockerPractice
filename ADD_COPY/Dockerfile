FROM ubuntu:latest
LABEL author='thoyaz'
LABEL authorsId='tz@gmail.com'
RUN apt update
RUN apt-get update && apt-get install apache2 -y
WORKDIR /var/www/html
COPY index.html .
CMD ["echo","Hello World"]