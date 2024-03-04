# Real-time Data Pipeline with Apache Kafka

This project provides a scalable and fault-tolerant real-time data pipeline using Apache Kafka for ingesting, processing, and analyzing streaming data.

## Prerequisites

Before getting started, make sure you have the following installed on your machine:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/Real-time-Data-Pipeline-with-Apache-Kafka.git
   ```

2. Navigate to the project directory:

   ```bash
   cd kafka-docker-compose
   ```

3. Start the Kafka cluster with Docker Compose:

   ```bash
   docker-compose up
   ```

   This command will download the required Docker images, create and start the containers for ZooKeeper and Kafka brokers, and set up the cluster according to the configurations specified in the Docker Compose file.

4. Verify the Kafka Cluster:

   - Use Kafka command-line tools to interact with the Kafka cluster.
   - Create topics, produce messages, and consume messages to verify the cluster's functionality.

## Configuration

- The `docker-compose.yml` file defines the configuration for ZooKeeper and Kafka brokers.
- Additional Kafka broker services can be added by following the same pattern as existing services.

## Accessing Services

- ZooKeeper: `localhost:2181`
- Kafka Broker 1: `localhost:9092`
- Kafka Broker 2: `localhost:9093`

## Cleanup

To stop and remove the Docker containers, use the following command:

```bash
docker-compose down
```

## Contributing

Feel free to contribute to this project by creating issues or submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
