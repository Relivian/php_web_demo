FROM php:8.2-apache

# Install dependencies and enable mysqli extension
RUN apt-get update && apt-get install -y \
    libmariadb-dev \
    && docker-php-ext-install mysqli \
    && docker-php-ext-enable mysqli

# Ensure apache2-foreground script exists
CMD ["apache2-foreground"]

