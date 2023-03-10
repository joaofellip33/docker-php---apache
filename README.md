# nome docker-compose.yml
version: "3"
services: 
  php:
    image: php:8.1.16-apache
    volumes:
      - .:/var/www/html/
    ports:
      - 80:80
