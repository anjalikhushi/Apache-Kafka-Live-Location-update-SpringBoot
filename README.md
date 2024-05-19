# Apache Kafka
  1. Apache Kafka is like a communication system that helps different parts of a computer system exchange data by publishing and subscribing to topics.
  2. Kafka is suitable for both offline and online message consumption. Kafka messages are persisted on the disk and replicated within the cluster to prevent data loss.
  3. Kafka is built on top of the ZooKeeper synchronization service.
  4. Zookeeper is used by Kafka brokers to determine which broker is the leader of a given partition and topic and perform leader elections.
  
 # Kafka Architecture
 
  <img width="650" alt="kafka" src="https://github.com/anjalikhushi/Apache-Kafka-Live-Location-update-SpringBoot/assets/82653640/dd974cae-3667-42cc-9dcc-ff1d1a8f9f9e">

  # Installation
  
    1. Download Kafka zip file from official website.
    2. Extract file
    3. Start Zookeeper 
    4. Start Kafka Server

  # To use Kafka with Console
  
    1.Create new topic with kafka-topics.
    2.Produce example message with kafka-console-producer.
    3.Consume the message with kafka-console consumer.

  # Created Two Spring Boot Projects (DeliveryBoy and EndUser App).
     
  # Output on console with the help of POSTMAN-
  
   # 1.
   <img width="650" alt="kf" src="https://github.com/anjalikhushi/Apache-Kafka-Live-Location-update-SpringBoot/assets/82653640/909a40ce-194b-4934-b13b-5a0461df302b">
   
   # 2.
   <img width="650" alt="kf1" src="https://github.com/anjalikhushi/Apache-Kafka-Live-Location-update-SpringBoot/assets/82653640/d80070d3-788e-4602-b384-59c738284b15">


  # Testing the App with a Live Load of 200K Messages

  # 1.
  <img width="650" alt="kf2" src="https://github.com/anjalikhushi/Apache-Kafka-Live-Location-update-SpringBoot/assets/82653640/4f1d0bae-95aa-414f-91d7-ce7761d9c0cb">
  
  # 2.
  <img width="650" alt="kf3" src="https://github.com/anjalikhushi/Apache-Kafka-Live-Location-update-SpringBoot/assets/82653640/86798f01-f4cd-46dc-be8e-95c2d921644c">



  


