Run producer & consumer in different command line terminals
```sh
mvn clean package
mvn exec:java -Dexec.mainClass="kafka.KafkaProducerExample"
mvn exec:java -Dexec.mainClass="kafka.KafkaConsumerExample"
```

Start entering text into the producer console and your should see it appearing in the consumer console.
