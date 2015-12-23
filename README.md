# Microservices

## The two microservices are running and registered
![](https://github.com/SirBargus/Laboratory-6-microservices/blob/master/img/1.png?raw=true)
![](https://github.com/SirBargus/Laboratory-6-microservices/blob/master/img/2.png?raw=true)

## The service registration service has the two microservices registered
![](https://github.com/SirBargus/Laboratory-6-microservices/blob/master/img/3.png?raw=true)

## A second account microservice is running in the port 4444
![](https://github.com/SirBargus/Laboratory-6-microservices/blob/master/img/4.png?raw=true)

##A brief report describing what happens when you kill the microservice with port 2222. Can the web service provide information about the accounts? Why?

When the account microservices in port 2222, stop send information about himself, it's stop working, to the registration microservers. Then the registration microserivces detects that microservices in port 2222 is down and it will replace by another account microservices (in our case which is running in port 4444)