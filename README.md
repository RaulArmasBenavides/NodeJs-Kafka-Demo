# NodeJs-Kafka-Demo

npm install

docker compose up -d             

To create topics 

 docker exec -it kafka1 bash -lc "/opt/kafka/bin/kafka-topics.sh --create --topic animals --bootstrap-server kafka1:19092 --partitions 3 --replication-factor 3"

 docker exec -it kafka1 bash -lc "/opt/kafka/bin/kafka-topics.sh --list --bootstrap-server kafka1:19092"