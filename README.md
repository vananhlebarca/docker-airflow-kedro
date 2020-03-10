## docker-airflow-kedro
This repository contains Dockerfile of apache-airflow, kedro and Kedro-airflow for Docker's automated build published to the public [Docker Hub Registry](https://hub.docker.com/repository/docker/vananhlebarca/docker-airflow-kedro).

## Installation
```
docker pull vananhlebarca/docker-airflow-kedro
```

## Build
```
docker build -t vananhlebarca/docker-airflow-kedro .
```

## Usage

```
docker run -d -p 8080:8080 -v /path/to/dags/on/your/local/machine/:/usr/local/airflow/dags vananhlebarca/docker-airflow-kedro-dependencies webserver

```
## UI link
Airflow: localhost:8080
