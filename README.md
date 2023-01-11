# Cinema

***

Welcome to Cinema API

## Installation:

```shell
git clone https://github.com/davidkrivko/Cinema-Docker.git
cd cinema_API
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
set DB_HOST=<your db hostname>
set DB_NAME=<your db name>
set DB_USER=<your db username>
set DB_PASSWORD=<your db user password>
set SECRET_KEY=<your secret key>
```

## Run with the Docker:

```shell
docker-compose build
docker-compose up
```

## Getting access

  You must create user and get JWT(token)

- create you user via /api/user/register/
- get token via /api/user/token/

## Features

- admin access
- JWT authentication
- CRUD for cinema sessions
- Creating movies with actors and genres, cinema halls
- Filtering movies by actors and genres, movie sessions by date
