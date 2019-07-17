# Docker simple LEMP stack

A simple docker stack for rapid prototyping.

## What's inside

- nginx:1.17.1-alpine 
- mariadb:10.3
- php:7.1-fpm

## usage

Simply run `docker-compose up -d` and navigate to `http://localhost`  you will see a HELLO page. 
This page is served from `./src/public` so make sure to put your web files there. 

## contribute

Feel free to contribute to make this config better