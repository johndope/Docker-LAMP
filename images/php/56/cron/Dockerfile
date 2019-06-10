FROM php:5.6-fpm
MAINTAINER johndopeit@gmail.com

# Install cron
RUN apt-get update && apt-get install -y cron

# Create the log file to be able to run tail
RUN mkdir /var/log/cron
RUN touch /var/log/cron/cron.log

RUN service cron start
