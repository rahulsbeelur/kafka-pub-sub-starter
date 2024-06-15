# kafka-pub-sub-starter

```docker
docker run -p 2181:2181 zookeeper
```

```docker
    podman run -p 9092:9092 \    
-e KAFKA_ZOOKEEPER_CONNECT=172.31.227.154:2181 \
-e KAFKA_ADVERTISED_LISTENERS=PLAINTEXT://172.31.227.154:9092 \
-e KAFKA_OFFSETS_TOPIC_REPLICATION_FACTOR=1 \
confluentinc/cp-kafka
```
