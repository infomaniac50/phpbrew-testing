FROM ubuntu:xenial

RUN apt-get update && apt-get install -y \
  php7.0 \
  php7.0-curl \
  php7.0-json \
  php7.0-cgi \
  php7.0-fpm \
  autoconf \
  automake \
  libxml2-dev \
  libcurl4-openssl-dev \
  libssl-dev \
  openssl \
  gettext \
  libicu-dev \
  libmcrypt-dev \
  libmcrypt4 \
  libbz2-dev \
  libreadline-dev \
  build-essential \
  libmhash-dev \
  libmhash2 \
  libxslt1-dev
RUN curl -L -O https://github.com/phpbrew/phpbrew/raw/master/phpbrew
RUN chmod u+x /phpbrew
RUN mv /phpbrew /usr/local/bin/
