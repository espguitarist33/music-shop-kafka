# music-shop-kafka
kafka configuration for music shop project.

As expected, start with docker-compose up -d

Example for creating a topic: docker-compose exec -it kafka kafka-topics.sh --create --bootstrap-server localhost:9092 --replication-factor 1 --partitions 1 --topic hello-kafka

List Topics: docker-compose exec -it kafka kafka-topics.sh --list --bootstrap-server localhost:9092
