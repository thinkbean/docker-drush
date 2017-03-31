FROM thinkbean/composer:php5
MAINTAINER Mike Milano <coder1@gmail.com>

ENV DRUSH_VERSION 8.1.10

RUN curl -fsSL -o /usr/local/bin/drush "https://github.com/drush-ops/drush/releases/download/$DRUSH_VERSION/drush.phar" && \
  chmod +x /usr/local/bin/drush

WORKDIR /app

ENTRYPOINT ["drush"]
