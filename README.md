DHT11 HUMIDITY TEMPERATURE MONITOR WITH NODEMCU ON THINGSPEAK
AIM: DHT11 Humidity Temperature Monitor on thingspeak  with  NODEMCU
Components required;

1.NodeMCU
2.DHT11 sensor
3.Thingspeak cloud server
4.Bread board
5.Jumper wires 
circuit diagram:


![image](https://github.com/aptiiotprojects/temperature-and-humidity-sensor-/assets/148192809/16b7841c-6923-4d81-a1bc-99b24c5c4005)

LIBRARY;


![image](https://github.com/aptiiotprojects/temperature-and-humidity-sensor-/assets/148192809/ed896f52-2cd3-4bb6-8dcf-3f1a2f64a30b)

 
BOARD LIBRARY:
DHT-sensor-library - https://github.com/adafruit/DHT-sensor-library/archive/refs/heads/master.zip
ESP8266wifi - https://github.com/ekstrand/ESP8266wifi/archive/refs/heads/master.zip

Install ESP8266 Add-on in Arduino IDE
To install the ESP8266 board in your Arduino IDE, follow these next instructions:
1.	In your Arduino IDE, go to File> Preferences


![image](https://github.com/aptiiotprojects/temperature-and-humidity-sensor-/assets/148192809/90f4c816-516f-4c15-91d7-54065b386ed6)


 

2.Enter http://arduino.esp8266.com/stable/package_esp8266com_index.json into the “Additional Boards Manager URLs” field as shown in the figure below. Then, click the “OK” button:


![image](https://github.com/aptiiotprojects/temperature-and-humidity-sensor-/assets/148192809/e8ada72a-7a9b-45ff-9863-874718b97c70)
 
Note: if you already have the ESP32 boards URL, you can separate the URLs with a comma as follows:

2.	Open the Boards Manager. Go to Tools > Board > Boards Manager…


  ![image](https://github.com/aptiiotprojects/temperature-and-humidity-sensor-/assets/148192809/6e05799e-23de-43fa-a168-b99fbec70837)

 
4.	Search for ESP8266 and press install button for the “ESP8266 by ESP8266 Community“:


![image](https://github.com/aptiiotprojects/temperature-and-humidity-sensor-/assets/148192809/713d0de8-9c8b-40aa-8d27-119ece48ff8a)


 

5.That’s it. It should be installed after a few seconds.
 Arduino code: https://github.com/aptiiotprojects/temperature-and-humidity-sensor-/blob/main/code.ino
 
1.ADD THE WIFI SSID AND PASSWORD IN THE PROGRAM
2.ADD API KEY IN THIS PROGRAM 
3.COPT THE API KEY IN THINKSPEAK CLOUD SERVER
THINGSPEAK CLOUD:


![image](https://github.com/aptiiotprojects/temperature-and-humidity-sensor-/assets/148192809/48483429-e5b2-4a3f-992f-cc996295219a)

 
CREATE AN ACCOUNT AND LOGIN INTO THINGSPEAL CLOUD SERVER


![image](https://github.com/aptiiotprojects/temperature-and-humidity-sensor-/assets/148192809/39894c9b-e166-4673-958a-187e59bc7813)

  
1.CREATE A CHANNEL AND SELECT TWO FEEDS FOR TEMPERATURE AND HUMIDITY
2.SAVE THE CHANNEL
API  KEYS;


![image](https://github.com/aptiiotprojects/temperature-and-humidity-sensor-/assets/148192809/9e101444-63d4-4d07-8e29-17e6fad537ef)

 
1.COPY THE WRITE API KEY AND PASTE IT IN ARDUINO PROGRAM
2.THEN RUN  THE PROGRAM




OPEN THE SERIAL MONITOR IN ARDUINO IDE


![image](https://github.com/aptiiotprojects/temperature-and-humidity-sensor-/assets/148192809/d21339ed-4abb-4471-99b0-d31763a8fc63)

 
1.CHECK THE TEMPERATURE AND HUMIDITY IN THE SERIAL MONITOR.
2.THEN OPEN THINKSPEAK CLOUD AND SELECT PRIVATE VIEW IN THE CHANNEL


![image](https://github.com/aptiiotprojects/temperature-and-humidity-sensor-/assets/148192809/151884eb-cf4d-4977-83e2-e82007a0a658)

DONE BY RANJITH KUMAR A


 




