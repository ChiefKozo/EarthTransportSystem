# EarthTransportSystem
Finding the shortest path between planets
Install spring plugin on Netbeans 8.0 or later
configure Maven in Netbeans to point to the local file on machine
Install and run RabbitMQ on local machine: username guest: password: guest
Download and import the five services into Netbeans IDE
Build the projects
Run the services in the following order
config
Eureka
gateway
earthtransportservice
earthtransportclient
Use a REST API to test the: http://localhost:9360/earth-transport-client/services/ws/PlanetRoutes?wsdl
