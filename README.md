After spinning up the containers you need to create an user

docker-compose exec webserver airflow users create --username admin --firstname admin --lastname admin --role Admin --email admin@example.org
