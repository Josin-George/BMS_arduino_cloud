Author: josingeorge

BMS_arduino _cloud is a project to realise the Arduino cloud Service which consist of a BMS to monitor a 3.7V Li-ion battery


Components used in circuit:
 1.ESP32 
 2.TP4056 charging module
 3.a pair of 1k ohm resitor for volateg divider
 4.Li-ion battery and case
 5.Jumper wires



* Utilising ESP32's 34th analog pin to take the battery voltage in the range of 0-4096 and converting it to 3.3V range.
* And uploaded the values of two variable 'bat_percentage' and 'voltage' to the Arduino Cloud instantly.
* Configured the IoT cloud using network credentials and device key.
