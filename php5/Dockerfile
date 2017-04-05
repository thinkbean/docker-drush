FROM thinkbean/php:5.6
MAINTAINER Mike Milano <coder1@gmail.com>

RUN apt-get update && apt-get install -y \
        curl \
        mysql-client \
        openssh-client \
        openssl \
        rsync \
    && composer global require drush/drush:8.1.10 \
    && mkdir $HOME/.drush \
    && mkdir $HOME/.ssh

WORKDIR /app/docroot

ENTRYPOINT ["drush"]
