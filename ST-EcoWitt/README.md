
# ST-EcoWitt
Process data from EcoWitt GW1000 and other EcoWitt Display receivers
for PWS and sensors

* Supported Receivers
	* GW1000
	* Display Consoles

* Supported Sensors
	* EcoWitt PWS Arrays
	* WH31 Temperature / Humidity Sensor
	* WH51 Soil Moisture Sensor
	* WH41 Air Quality Sensor

## Configuration
- Default Short Poll:  1 Minutes (60 Seconds)
	- Not Used
- Default Long Poll: 10 Minutes (600 Seconds)
	- Not Used


- WS View Device Configuration
	- Select the receiver from Devices
	- More -> Weather Services
	- Next 4 times to the Customized option
	- Server IP = Polisy IP Address
	- Path = /data/report/
	- Port = listenPort defined in NS configuration
		Upload Interval = Interval to send data to NS

## Node Server Configuration

- listenPort = Port defined in Weather Service of GW1000
	Must be integer example: 8181, 8282, 8383, 8989