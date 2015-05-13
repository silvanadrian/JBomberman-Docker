# JBomberman-Docker
Dockerfile for the Bomberman Clone to start the JBombermanServer and a RabbitMQ Broker.


#Build:
	docker build -t jbomb .
	
	
#Run:

	docker run -d -p 5672:5672 -p 15672:15672 jbomb


#To Dos:
* Use a Proxy to switch between diffrent Servers (diffrent subdomains) -> or even randomize this and just assign players to a Server
* Nicer option than Curl the key of the SIgning Key and the Jar File of JBomberman

