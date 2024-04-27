# datasystem
This project to explore the tools related for platform (apache-beam, airflow, docker, docker-compose etc).

# docker-compose_yaml

https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html

https://airflow.apache.org/docs/apache-airflow/2.9.0/docker-compose.yaml

```
curl -LfO 'https://airflow.apache.org/docs/apache-airflow/2.9.0/docker-compose.yaml'

mkdir -p ./dags ./logs ./plugins ./config

echo -e "AIRFLOW_UID=$(id -u)\n AIRFLOW_GID=0" > .env

docker compose up airflow-init
``` 

