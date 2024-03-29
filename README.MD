# Multi-Database Docker Setup

This repository contains Docker Compose configurations for setting up Kafka, PostgreSQL, and Vertica databases.

## Structure

- `Kafka-Installation/`: Contains Docker Compose configuration for setting up a Kafka service.
- `PostgreSQL-Installation/`: Contains Docker Compose configuration for setting up a PostgreSQL service.
- `Vertica-Installation/`: Contains Docker Compose configuration for setting up a Vertica service.

## Usage

To start a service, navigate to its directory and run the following command:

```sh
docker-compose up -d

For example, to start the Kafka service, you would do:

cd Kafka-Installation
docker-compose up -d

Services
Kafka
The Kafka service includes a Kafka server and a Zookeeper server. The Kafka server is accessible at localhost:9092.

PostgreSQL
The PostgreSQL service includes a PostgreSQL server and an Adminer server. The PostgreSQL server is accessible at localhost:5432, and the Adminer server is accessible at localhost:8080.

Vertica
The Vertica service includes a Vertica server. The Vertica server is accessible at localhost:5433.

Note
Please ensure Docker and Docker Compose are installed on your machine before running these services.