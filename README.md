# VMware CodeHouse 2022
This document will serve as guidance for attendees and mentors of VMware CodeHouse 2022.

The goal of the hackathon will be to create an application that furthers STEM education and/or Diversity & Inclusion. This application should leverage Asynchronous Messaging technology for communication flow and should be well documented so it can be shared as an example application after the hackathon.

# Required reading
To make sure you are comfortable with the framework we will be using, please read through the following documents well in advance:

## What is Asynchronous Messaging 
Asynchronous Messaging is a communication method where participants on both sides of the communication have the freedom to start, pause, and resume messaging on their own terms, eliminating the need to wait for a direct live connection (aka synchronous messages).

Kafka is one of typical implementation as asynchronous messaging. Please refer to here to start https://kafka.apache.org/intro. 
Activemq and RabbitMQ are similar implementation.  

## How is Asynchronous Messaging Used
### Event Driven Service Communication
Asynchronous Messaging is widely used for service asynchronous communication as a critical component for Event Driven Architecture.
Example: https://github.com/ewolff/microservice-kafka 

### Virtual Communication 
Asynchronous Messaging is also widely used for virtual communication. Customer does not need to wait for a customer representative and can work on their schedule and any of their client.  The backend service can work with AI and machine learning together to present required info to customer with asynchronous communication.  

Example: ChatBot with Asynchronous Messaging:  https://www.freecodecamp.org/news/simple-chatops-with-kafka-grafana-prometheus-and-slack-764ece59e707/

### Streaming Processing
Asynchronous Messaging is also used for streaming processing, which can connect multi data pipeline to process data asynchronously and generate interesting results. Please refer to https://github.com/confluentinc/kafka-streams-examples for more details. 

Example:  http://www.infolace.com/blog/2016/07/14/simple-spatial-windowing-with-kafka-streams/

# Completion of pre-req tasks
Once you have completed these tasks, make a pull request to this repository with a Markdown file in this format:

firstname-lastname.md

I've finished reading through the pre-req docs and finished one of the Oauth flow in the above mentioned playground.
