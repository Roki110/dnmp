# DNMP

DNMP is Docker Nginx MySQL PHP

It's like LAMP (Linux Apache MySQL PHP) but I purpose a variant with docker and nginx.
I use official images for each to keep it easy to maintain.

# Why use it ?

You can use this to dev application for the web.
/!\ WARNING: It shouldn't be use for production environment. Create dedicated images of your app in a production environment

# How to use it

Put your app in /web and you can access to your via http://<host-ip>:8000
Your database is store in /db

To change configuration it's in /config/<app>

# Apps version

Currently apps version are :
- nginx 1.25.2
- php-fpm 8.2.8
- mysql 8.0.34
- phpmyadmin 5.2.1

I try to use alpine based images for his lightness or if there is no official images that use alpine as base. I choose debian
