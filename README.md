echo -e "AIRFLOW_UID=$(id -u)" > .env

docker-compose up airflow-init

default user airflow
default password airflow

https://betterdatascience.com/apache-airflow-write-your-first-dag/