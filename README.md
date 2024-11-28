## Project Overview
This project demonstrates how to consume objects from Kafka. It is implemented using Spring Boot.
The consumer config is created programmatically using ConsumerFactory.

### How to Run
1. Start Zookeper with this command:  
   <em>bin/windows/zookeeper-server-start.bat</em>


2. Start Kafka server with this command:  
   <em>bin/windows/kafka-server-start.bat</em>


3. Start the consumer app  
Verify customer events are received from producer