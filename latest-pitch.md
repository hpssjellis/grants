
**Project:**

Helium Arduino Portenta Lora Vision Shield Sensor Actuator Tutorials for Non-Engineers


**Note:** I have reduced the scope of this grant and removed the Machine Learning component as that may be better suited to a follow up grant next year.

-----


**Elevator Pitch:**

The Helium People's Network needs everyday people to be able to use both the Hotspots and their own Devices. In my opinion only big companies with Mechatronic Engineers using ESP32's are able to create products that effectively use HNT.

I believe the network's success is centered on many people being able to make LoRaWan low power long distance solutions for their family and small business needs. The simplicity of the Arduino products is 
legendary and the Portenta is a beast, with it's dual core, 160 pin base and shields for Vision, Microphone, sd card, Ethernet and LoRaWan. The PortentaH7 is the perfect choice for the technology capable Helium Hotspot owner.

I have the unique ability to simplify complex technology and the teaching experience to create a base set of tutorials to allow anyone to use the Helium Network to it's full potential.

## What it is all about: 

Here I show my Bobcat Miner beside an Arduino Portenta with the LoRa Vision Shield attached using the 2 x 80 pin attachments and a 915 MHz antenna powered by a regular cell phone charger. (LiPo or coin cell options on the large breakout board not shown)


![image](https://user-images.githubusercontent.com/5605614/132133375-a1df96b3-161e-411d-bdae-402925b79550.png)





-----


**Total Fiat/HNT ask:** 

$9000 USD to connect the LoRaWan Arduino Pro Portenta LoRa Vision Shield to the Helium Network with Educational videos showing typical Arduino users 
how to connect and use the Helium Network, including how to use the MQTT servers and Helium Console that are an integral part of the Helium data collection techniques






-----


**Code Repos of team of key applicant:**

The Final Product Github Link: [Maker100](https://github.com/hpssjellis/maker100)


The Final Product Video Playlist: [Youtube Maker 100 Videos](https://www.youtube.com/playlist?list=PL57Dnr1H_egv1FVzAcCZVeANJMs3Hta05)


The Final Product Library for the Arduino IDE: [portenta-pro-community-solutions](https://github.com/hpssjellis/portenta-pro-community-solutions)

My Github Profile: [Jeremy Ellis Github Profile](https://github.com/hpssjellis) 




----

**Project Details:**

- Background: The Arduino Portenta https://store.arduino.cc/usa/portenta-h7 is the new $103.40 USD "Pro" Arduino board with impressive abilities (easy Arduino programming of this dual core, 160 pin, Wifi, BLE, I2C, UART, SPI, Coincell and LiPo connector breakout board.) especially when combined with the $63.00 USD LoRa Vision Shield https://store.arduino.cc/usa/portenta-vision-shield-lora  and the optional $45.99 USD Breakout board https://store.arduino.cc/usa/portenta-breakout. The Vision shield with 320px x 320px GRAYSCALE camera and dual microphones brings multiple sensor possiblities to Makers and Professional businesses alike. 

## Arduino Pro PortentaH7

![PortentaH7small](https://user-images.githubusercontent.com/5605614/132133468-9d787a43-3d0b-41f8-97f4-7bb5fa66680a.jpg)



## LoRa Vision Shield
This snaps to the back of the PortentaH7 using 2 x 80 pin high Density connectors.


![lora-vision-small](https://user-images.githubusercontent.com/5605614/132133504-dfbcf4fb-961d-4bc1-82bb-165a1d87c438.jpg)


## Optional BreakoutBoard, note the Vision shields can still snap to the back of the breakout board!

![image](https://user-images.githubusercontent.com/5605614/132133509-777da3cc-c121-416c-88ea-c8cba7a1ae94.png)





## Problem

- Problem (as of May 2021): Unlike many LoRa capable boards the Portenta does not give direct access to the LoRa module, making most LoRa and LoRaWan example code useless. The Arduino MKRWAN library can connect to the TTN (TheThingsNetwork) in Europe but has some issues connecting in North America.  
- Problem to Solve: Helium connectivity in North America does not work with the present May 2021 Arduino examples. 
- Connecting is only the first step, simple sensors and actuator examples are also needed.

- Solution: I plan to simplify getting Portenta sensors and actuators working on the Helium Network. 
- First with basic connectivity, then simplifying Cayenne MQTT server presentation of the uploaded data.
- (Update: Summer 2021) I have spent several months looking into solutions and now with recent improvements to the Arduino MKRWAN library I have 2 proven methods to connect to Helium in North America






-----

**Roadmap:**

| Milestone + Date &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Deliverable | Summary | Cost |
| --- | --- | --- | --- |
|  MS#1 April 2021 | Research Arduino Portenta Pro Dual Core 160 pin microcontroller |     Done    [Generic Portenta Github](https://github.com/hpssjellis/my-examples-for-the-arduino-portentaH7)       |     $500 USD         |
|  MS#2  June 2021| Research LoRa and LoRaWan abilities for the Arduino Portenta Pro LoRa Vision Shield, using the Murata Module and the [GrumpyOldPizza](https://github.com/GrumpyOldPizza/ArduinoCore-stm32l0) Library |     Done    [Portenta Murata Module LoRa Control](https://github.com/hpssjellis/portenta-lora-murata-stm32lo)       |     $500 USD         |
|  MS#3  August 2021| Research LoRa and LoRaWan abilities for the Arduino Portenta Pro LoRa Vision Shield, using the [MKRWAN](https://github.com/arduino-libraries/MKRWAN) Arduino Library |     Done  [MKRWAN Relevant Issues](https://github.com/arduino-libraries/MKRWAN/issues?q=is%3Aissue+portenta)        |     $500 USD         |
|  MS#4    September 2021       |        Create Multiple Educational videos of connecting Sensors and Actuators to the Arduino Portenta        |     On Going  [Youtube Playlist here](https://www.youtube.com/watch?v=3E5KUT115xY&list=PL57Dnr1H_egv1FVzAcCZVeANJMs3Hta05&index=7)     |     $500 USD       |
|  MS#5    October 2021         |        Connect the Portenta to the Helium Network                                               |     On Going [c-b-b-helium-cayenne-us915.ino](https://github.com/hpssjellis/portenta-pro-community-solutions/blob/main/examples/c-portenta-vision-shields/c-b-lorawan-specific/c-b-b-helium-cayenne-us915/c-b-b-helium-cayenne-us915.ino)        |     $1000 USD          |
|  MS#6    December 2021         |        Create several examples (code and/or notes/images) of sending data on the Helium network                                             |     On Going [c-b-lorawan-specific](https://github.com/hpssjellis/portenta-pro-community-solutions/blob/main/examples/c-portenta-vision-shields/c-b-lorawan-specific/)        |     $1000 USD          |
|  MS#7    April 2022         |         Create Multiple Educational videos of the multiple steps to connect the Arduino Portenta with LoRa Vision Shield to the Helium Network using MQTT servers such as https://adafruit.io and how to extract useful information from it                                       |     On Going [maker100#28](https://github.com/hpssjellis/maker100#28)        |     $1000 USD          |
|  MS#8    June 2022         |        Create a https:hackster.io example of the above code, videos and Helium sensor solutions, (Possibly publish to other social media learning sites: https://hackaday.com/, https://medium.com etc)                                             |     Note Yet Started [my Hackster.io area](https://www.hackster.io/jeremy-ellis/)        |     $1000 USD          |
|  MS#9    July 2022         |       Send PR requests to the relevant Arduino libraries to have my Helium examples on the Arduino MBED core                                            |     Note Yet Started [ArduinoCore-mbed Pull Requests](https://github.com/arduino/ArduinoCore-mbed/pulls)        |     $500 USD          |
|  MS#10    July 2022         |       Send PR requests to the the Helium docs to inform a wider Helium audience of how to use the Arduino Portenta                                           |     Note Yet Started [helium/docs](https://github.com/helium/docs)        |     $500 USD          |
|  MS#11    July 2022         |       Send PR requests to the the Helium LongFi Arduino Github with my examples for using the Arduino Portenta with Helium.                                          |     Note Yet Started [longfi-arduino](https://github.com/helium/longfi-arduino)        |     $500 USD          |
|  MS#12     August 2022         |         Create a Github summary of all facets of Learning microcontroller sensors, actuators and how to send the information to the Helium Network      |     On Going [Maker100 Course](https://github.com/hpssjellis/maker100)     |    $1000 USD       |
|  MS#13    August 2022       |        Make an Arduino Library of useful code and examples              |     On Going  [My Arduino IDE Library called the portenta-pro-community-solutions](https://github.com/hpssjellis/portenta-pro-community-solutions)       |    $500 USD         |
|  MS#14     August 2022         |        Write part 2 of this DeWi grant to include Machine Learning and how to use the Portenta with TinyML to extract meaning from the collected sensor data. This would mainly use the Arduino Portenta vision shield but could also include other sensors and how to send these Machine Learning conclusions to the Helium Network. This is relevant since the Helium Netowrk has reduced data transmission to increase battery life and is not made to send vision information to the cloud to be processed. Machine Learning allows the data to be processed on the device and then to only send the conclusions of the analysis to the Helium network.     |     Not Yet Started [DiWi Grant Issues page](https://github.com/dewi-alliance/grants/issues)     |    $0 USD       |
| --- | --- | --- | Total $9000.00 USD |



----

## Generic Links related to this Project

Maker100 Robotics Curriculum: [https://github.com/hpssjellis/maker100](https://github.com/hpssjellis/maker100)

Maker100 Video Playlist [https://github.com/hpssjellis/portenta-pro-community-solutions/blob/main/examples/a-portentaH7-examples/a-a-hello-blink/a-a-hello-blink.ino](https://github.com/hpssjellis/portenta-pro-community-solutions/blob/main/examples/a-portentaH7-examples/a-a-hello-blink/a-a-hello-blink.ino)


Twitter: [https://twitter.com/rocksetta](https://twitter.com/rocksetta)
                 
Website: [https://www.rocksetta.com/](https://www.rocksetta.com/ ) 
                
  
## Older Links   
   
Youtube Arduino Playlist: [https://www.youtube.com/watch?v=bVIdH92dcqg&list=PL57Dnr1H_egtm0pi-okmG0iE_X5dROaLw](https://www.youtube.com/watch?v=bVIdH92dcqg&list=PL57Dnr1H_egtm0pi-okmG0iE_X5dROaLw)
                
Robotics Curriculum with Video Series:   [https://github.com/hpssjellis/particle.io-photon-high-school-robotics](https://github.com/hpssjellis/particle.io-photon-high-school-robotics)
                
Arduino Portenta Solutions: [https://github.com/hpssjellis/my-examples-for-the-arduino-portentaH7](https://github.com/hpssjellis/my-examples-for-the-arduino-portentaH7)

Machine Learning using TensorflowJS: [https://www.rocksetta.com/tensorflowjs/](https://www.rocksetta.com/tensorflowjs/)
 
 
 
## Relevant Experience by Jeremy Ellis

I have taught coding for 30 years, taught robotics for 7 years, developed my own Robotics curriculum. Have a Chemistry Degree, An Education Degree and a Diploma in Counseling. I teach High School Tecnology including:Robotics, Coding, Animation and 3D Printing. I taught myself Machine learning. I am an Edge Impulse Ambassador https://www.edgeimpulse.com/ . I have a class set of the Arduino Portenta, with LoRa Vision Shields and Breakout boards for teaching Robotics during the next few years. 









