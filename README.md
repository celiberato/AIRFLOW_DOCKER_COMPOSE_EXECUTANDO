# AIRFLOW_DOCKER_COMPOSE_EXECUTANDO

curl -LfO 'https://airflow.apache.org/docs/apache-airflow/stable/docker-compose.yaml'

mkdir -p ./dags ./logs ./plugins

docker-compose up -d
