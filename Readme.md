
## Requirements
* Docker
* Postgres - image docker: 'postgres:11'
* Mongo
* Redis


### docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres:11   

### docker run --name mongobarber -p 27017:27017 -d -t mongo ###

### docker run --name redisshine -p 6379:6379 -d -t redis:alpine ###


