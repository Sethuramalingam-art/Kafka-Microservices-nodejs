# Kafka-Microservices-nodejs

Apache kafka is a open source distributed event streaming platform used by thousands of companies for high prfoming data pipelines streaming analystics data integration and 
mission critical apps

why kafka?
I have 2 apps

App1 and App2 

now I want to send a data from App1 to App2 but App2 is not available to recieve the data. Then App2 will lose the data so it will affect App2 businesses. To overcome this
Kafka will come into the place. 

So we will include messaging systems like kafka, rabbit MQ , Redis between App1 and App2. Now App1 will send message/ dat to kafka,
Once done this one when App2 is available it will collect the data from Kafka.

Real time uses.
When we have different no of server like 
frontend
hadoop
chat server 

from these server we need to pass the data to servers like
data base
security systems
real time monitoring

So connections are different for data share like 
frontend -> data base server
frontend -> security systes

1.so no of connections high

2.Data format need to share diff formats for each servers are diff
So frontend server will share payload structure to data base server is different when frontend share payload structure to secutiry server systems

3.comnnection types are differenct 

so to fix this one we have to include messaging system called kafka

instead of connection servers directly 
frontend -> kafka -> database server 
So it will eliminate no of connections issues, data format issues.


PFA-> image
Kafka works with 
publiser/subscriber model pub/sub model


APP1 is publiser . it publish the data as message/ event to message broker and subscriber can be only listen the message from the message broker

