FROM thinkbean/composer:php5
MAINTAINER Mike Milano <coder1@gmail.com>

RUN composer global require drush/drush:8.1.10

WORKDIR /var/www/html

ENTRYPOINT ["drush"]
