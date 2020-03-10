# Connecting to broker


  - In KAFKA_ADVERTISED_LISTENERS replace hostname with your server IP in 
docker-compose.yaml file
  - make sure ports 22181, 32181, 42181, 19092, 29092, 39092 are  accessible 
  - Run "docker-compose up"
  - wait till kafka cluster starts
  - Now you can connect to kafka cluster using any kafka tool 
    zookeeper  hostname:22181 or hostname:32181 or hostname:42181
    broker     hostname:19092 or hostname:29092 or hostname:39092
  - Zookeeper data and logs can be found in /zoo1 , /zoo2, /zoo3. Directories on host
  - Kafka data can be found in /kafka1, /kafka2, /kafka3 on host


