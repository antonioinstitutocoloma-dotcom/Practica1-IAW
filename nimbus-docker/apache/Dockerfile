FROM php:8.2-apache
COPY conf/*.conf /etc/apache2/sites-available/
RUN a2ensite alpha-docs.net beta-docs.net && a2dissite 000-default.conf
