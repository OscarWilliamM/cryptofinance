# Sistema Financeiro de CryptoAtivos com FastApi

**Tecnologias Usadas

**FastAPI, PostgreSQL, SQLAlchemy, requests with AIOHTTP**

# Dependecies
* Docker
* Docker-compse
* Python >= 3.8
* Pip

# How to run
Add project path at `PYTHONPATH` variable in `.env` file.

Start **postgres** database and **pgadmin**
```shell
docker-compose up -d
```

Install python dependencies
```shell
pip install
```

Populate database
```shell
python populate_bd.py
```

Start application
```shell
fastapi dev main.py
```
