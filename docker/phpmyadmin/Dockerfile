FROM phpmyadmin/phpmyadmin:latest

ARG PMA_SECRET_KEY

ENV PMA_SECRET_KEY=${PMA_SECRET_KEY}

# Copy config file into container
COPY config.inc.php /etc/phpmyadmin/config.inc.php

# Set the user and group
USER www-data:www-data
