### setup airflow user
echo -e "AIRFLOW_UID=$(id -u)" > .env

### step to start airflow
1. docker compose up airflow-init
2. docker compose up
