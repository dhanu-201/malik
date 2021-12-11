# malik
Awesome Compose Awesome
logo

A curated list of Docker Compose samples.

These samples provide a starting point for how to integrate different services using a Compose file and to manage their deployment with Docker Compose.

Note:

The following samples are intended for use in local development environments such as project setups, tinkering with software stacks, etc. These samples must not be deployed in production environments.

Contents
Samples of Docker Compose applications with multiple integrated services.
Single service samples.
Basic setups for different platforms (not production ready - useful for personal use).
Samples of Docker Compose applications with multiple integrated services
ASP.NET / MS-SQL - Sample ASP.NET core application with MS SQL server database.
Elasticsearch / Logstash / Kibana - Sample Elasticsearch, Logstash, and Kibana stack.
Go / NGINX / MySQL - Sample Go application with an Nginx proxy and a MySQL database.
Go / NGINX / PostgreSQL - Sample Go application with an Nginx proxy and a PostgreSQL database.
Java Spark / MySQL - Sample Java application and a MySQL database.
NGINX / ASP.NET / MySQL - Sample Nginx reverse proxy with an C# backend using ASP.NET
NGINX / Flask / MongoDB - Sample Python/Flask application with Nginx proxy and a Mongo database.
NGINX / Flask / MySQL - Sample Python/Flask application with an Nginx proxy and a MySQL database.
NGINX / Go - Sample Nginx proxy with a Go backend.
NGINX / WSGI / Flask - Sample Nginx reverse proxy with a Flask backend using WSGI.
PostgreSQL / pgAdmin - Sample setup for postgreSQL database with pgAdmin web interface
React / Spring / MySQL - Sample React application with a Spring backend and a MySQL database.
React / Express / MySQL - Sample React application with a Node.js backend and a MySQL database.
React / Express / MongoDB - Sample React application with a Node.js backend and a Mongo database.
React / Rust / PostgreSQL - Sample React application with a Rust backend and a Postgres database.
React / Nginx - Sample React application with Nginx.
Spring / PostgreSQL - Sample Java application with Spring framework and a Postgres database.
Single service samples
Angular
Spark
VueJS
Flask
PHP
Traefik
Django
Minecraft server
Plex
Portainer
Wireguard
Basic setups for different platforms (not production ready - useful for personal use)
Gitea / PostgreSQL
Nextcloud / PostgreSQL
Nextcloud / Redis / MariaDB
Pi-hole / cloudflared - Sample Pi-hole setup with use of DoH cloudflared service
Prometheus / Grafana
Wordpress / MySQL
Getting started
These instructions will get you through the bootstrap phase of creating and deploying samples of containerized applications with Docker Compose.

Prerequisites
Make sure that you have Docker and Docker Compose installed
Windows or macOS: Install Docker Desktop
Linux: Install Docker and then Docker Compose
Download some or all of the samples from this repository.
Running a sample
The root directory of each sample contains the docker-compose.yaml which describes the configuration of service components. All samples can be run in a local environment by going into the root directory of each one and executing:

docker-compose up -d
Check the README.md of each sample to get more details on the structure and what is the expected output. To stop and remove all containers of the sample application run:

docker-compose down
Contribute
We welcome examples that help people understand how to use Docker Compose for common applications. Check the Contribution Guide for more details.
