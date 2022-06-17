# Services
To run services run: `./run_services.sh`
If it does fail change it to executable with `chmod +x run_services.sh`
### Postgresql (HISTORICAL DATA)
jdbc url: `jdbc:postgresql://localhost:8001/postgres`

* hostname: `localhost`
* port: `8001`
* username: `postgres`
* password: `postgres`
* database: `postgres`

### Postgresql (MAIN DATA)
jdbc url: `jdbc:postgresql://localhost:8002/postgres`

* hostname: `localhost`
* port: `8002`
* username: `postgres`
* password: `postgres`
* database: `postgres`

### RabbitMQ
amqp url: `amqp://guest:guest@localhost:5672/`
admin url: `http://localhost:15672`

* username: `guest`
* password: `guest`
* vhost: `/`
