# local-dev-services
A collection of common services to aid in local development

Here you will find the following services...
* Postgres
  * [http://localhost:5423](http://localhost:5423)
  * uname: postgres
  * password: 1234
* Redis
  * [http://localhost:6379](http://localhost:6379)
* Zookeeper
  * [http://localhost:2181](http://localhost:2181)
* Kafka
  * [http://localhost:9092](http://localhost:9092)

## Prerequisites

1. Docker 1.10+
1. Git
1. Node v4+
1. Yarn 0.16+ or Npm v3+

## Getting Started

1. `git clone git@github.com:n8waldo/local-dev-services.git && cd local-dev-services`
1. `yarn # or npm install`
1. `yarn start # or npm start`
1. `docker-compose ps # list out the running processes after a successful start`

## Stopping services

 1. `yarn stop`
