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
