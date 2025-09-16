# Kafka Stock Market Real Time Data Engineer Project
---

## Architecture
![Kafka Stock Market Architecture](images/Architecture.jpg)
---

## Tech Stack
1. Python Jupyter Notebook
2. Amazon Web Service (AWS)
    *  AWS EC2
    *  AWS S3
    *  AWS Glue Crawler
    *  AWS Glue Catalog
    *  Amazon Athena
3. Apache Kafka
---

## Tasks
1. Create AWS EC2 Instance
2. Create AWS S3
3. Connect to AWS EC2
4. Download Requirements
    * Apache Kafka compress version
    * java
5. Start Zookeeper
6. Start Kafka-Server
7. Create Topic
8. Start Producer
9. Start Consumer
10. Create KafkaProducer.ipynb 
    * Create Producer 
    * Read file indexProcessed.csv
    * Streaming Data
11. Create KafkaConsumer.ipynb
    * Create Consumer
    * Consume data from Producer
    * Build pipeline load to AWS S3
12. Create AWS Glue Crawler to explore schema and save to database
13. Query Real Time data by Amazon Athana