# Awesome Compose [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![logo](awesome-compose.jpg)

> A curated list of Docker Compose samples.
These samples provide a starting point for how to integrate different services using a Compose file and to manage their deployment with docker-compose.

## Getting started

These instructions will get you through the bootstrap phase of creating and
deploying samples of containerized applications with docker-compose.

### Prerequisites

* Make sure that you have Docker and docker-compose installed
  * Windows or macOS:
    [Install Docker Desktop](https://www.docker.com/get-started)
  * Linux: [Install Docker](https://www.docker.com/get-started) and then
    [docker-compose](https://github.com/docker/compose)
* Download some or all of the samples in the `samples` directory

### Running a sample

The root directory of each sample contains the docker-compose.yaml which
describes the configuration of service components. All samples can be run in
a local environment by going into the root directory of each one and executing:

```console
docker-compose up -d
```

Check the `README.md` of each sample to get more details on the structure and
what is the expected output.
To stop and remove the all containers of the sample application run:

```console
docker-compose down
```

## Contents

*Samples of Docker Compose applications with multiple integrated services:*

- [`ASP.NET / MS-SQL`](samples/aspnet-mssql) -- sample ASP.NET core application
  with MS SQL server database
- [`Go / NGINX / MySQL`](samples/nginx-golang-mysql) -- sample Go application
  with an Nginx proxy and a MySQL database
- [`Go / NGINX / PostgreSQL`](samples/nginx-golang-postgres) -- sample Go
  application with an Nginx proxy and a PostgreSQL database
- [`Java Spark / MySQL`](samples/sparkjava-mysql) -- sample Java application and
  a MySQL database
- [`NGINX / Flask / MongoDB`](samples/nginx-flask-mongo) -- sample Python/Flask
  application with Nginx proxy and a Mongo database
- [`NGINX / Flask / MySQL`](samples/nginx-flask-mysql) -- sample Python/Flask
  application with an Nginx proxy and a MySQL database
- [`NGINX / Go`](samples/nginx-golang) -- sample Nginx proxy with a Go backend
- [`React / Spring / MySQL`](samples/react-java-mysql) -- sample React
  application with a Spring backend and a MySQL database
- [`React / Express / MySQL`](samples/react-express-mysql) -- sample React
  application with a NodeJS backend and a MySQL database
- [`Spring / PostgreSQL`](samples/spring-postgres) -- sample Java application
  with Spring framework and a Postgres database

*Single service samples:*
- [`Angular`](samples/angular)
- [`Spark`](samples/sparkjava)
- [`VueJS`](samples/vuejs)

## Contribute

We welcome examples that help people understand how to use docker-compose for
common applications.