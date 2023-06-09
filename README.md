# Kafka Deployment using AWS

Kafka Deployment using AWS
In scope of MoleCare application design and development and my master science project, I made a research how to use Kafka in AWS and built a system for running DNN service, which integrated to MoleCare backend application using Kafka.
In scope of work
Kafka can be available on the Internet if the ports are configured. That is why I setup VPC and I configure users and groups for allowing Kafka keeping data on the filesystem.

![Alt text](./screens/AWS-EC2-kafka-29.PNG?raw=true "Title")

Also, I create two topics in Kafka. One topic is for request with mole images, and another one is the queue of prediction results.

![Alt text](./screens/img.png?raw=true "Title")

Steps
Launch instance
![Alt text](./screens/AWS-EC2-kafka-1.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-2.PNG?raw=true "Title")
SSH client setup
![Alt text](./screens/AWS-EC2-kafka-3.PNG?raw=true "Title")
Install Kafka
![Alt text](./screens/AWS-EC2-kafka-6.PNG?raw=true "Title")
Set zookeeper properties
![Alt text](./screens/AWS-EC2-kafka-7.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-8.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-9-run-to-setup-env-variables.PNG?raw=true)
![Alt text](./screens/AWS-EC2-kafka-10.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-11.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-12.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-13.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-14.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-15.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-16.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-17.PNG?raw=true "Title")
Run zookeeper
![Alt text](./screens/AWS-EC2-kafka-18.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-19.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-20.v?raw=true "Title")
Run Kafka
![Alt text](./screens/AWS-EC2-kafka-21.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-22.PNG?raw=true "Title")
Create topics
![Alt text](./screens/AWS-EC2-kafka-23.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-24.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-25.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-26.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-27.PNG?raw=true "Title")
![Alt text](./screens/AWS-EC2-kafka-28.PNG?raw=true "Title")
