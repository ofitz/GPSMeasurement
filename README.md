GPS tracking area with esp8266 and visualization Platform
=========================================================

##The idea
Build a small device with 1.8 Display and three buttons. First button is for start tracking my position over GPS, second button is to mark and save the next gps position and the third button is for mark the end of area mesuaring.

![N|Solid](https://github.com/ofitz/GPSMeasurement/blob/master/images/Areamesure.png)

The GPS Point are pushed to the Cloud and the Virtual Machine calculated the area in m² using the Points. 

###For tracking and visualization the area i need:

####Hardware:
* Microcontroller: ESP8266
* GPS Modul: GY-NEO6MV2
* TFT Shield 1.8" 

####Software and Cloud:
* Azure IoT Platform
* Azure Linux VM
* Azure Database 
* Azure Web-App
* Azure Powe

###Steps
####Config/flash ESP8266
####ESP8266 connect with GPS Modul
####ESP8266 connect with TFT Shield 1.8
####Config Azure IoT Platform
####Register the "Aremesure" in the IoT Cloud
####Send GPS Points too the IoT Cloud
####Receive GPS Points from IoT Cloud