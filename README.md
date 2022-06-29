# Pub-Sub Messaging with Laravel and Apache Kafka Example (Publisher)

## Connect to database

To connect to MySQL database from your main machine via Navicat or Sequel Pro, you should connect to `127.0.0.1` and port `3407`. The username and password for databases is `laravel / laravel`.

```yml
host: 127.0.0.1
port: 3407
database: laravel
username: root
password: 
```

## Kafka settings

ENV settings:
```
KAFKA_BROKERS=localhost:9092
KAFKA_DEBUG=false

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```
