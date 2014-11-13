MQTT-Client
===========
Steps:

1) Go to the project folder 
	cd MQTT-Client

2)Do a maven install
	mvn clean install

3)Make sure Mosquitto  broker is running

4)Run the Sample.java with below arguments,

a)For MQTT Subscriber
-a subscribe -t Sample/Java

b)For MQTT Publisher
-t Sample/Java -s 1 -m "customized message"

Note:
Make Mosquito broker is installed from http://mosquitto.org/download/

