
**Project:**

Helium Arduino Portenta Lora Vision Shield Sensor Actuator Machine Learning Tutorials for Non-Engineers


-----


**Elevator Pitch:**

The Helium People's Network needs everyday people to be able to use both the Hotspots and their own Devices. Machine Learning on Edge Devices fits perfectly with the Helium 
Network low bandwidth and low power consumption, but presently only big companies with Mechatronic Engineers using ESP32's are able to create products that effectively use HNT.

I believe the networks success is centered on many people being able to make TinyML solutions for their family and small business needs. The simplicity of the Arduino products is 
legendary and the Portenta is a beast, with it's dual core, 160 pin base and shields for Vision, Microphone, sd card, Ethernet and LoRaWan. The PortentaH7  is the perfect choice for the technology capable Helium Hotspot owner.

I have the unique ability to simplify complex technology and the teaching experience to create a base set of tutorials to allow anyone to use the Helium Network to it's full potential.

## What it is all about: 

A bobcat Miner beside an Arduino Portenta with the LoRa Vision Shield attached using the 2 x 80 pin attachments and a 915 MHz antenna powered by a regular cell phone charger. (LiPo or coin cell options not shown)


![image](https://user-images.githubusercontent.com/5605614/132133375-a1df96b3-161e-411d-bdae-402925b79550.png)





-----


**Total Fiat/HNT ask:** 

$7000 USD to connect the Machine Learning capable Arduino Pro Portenta LoRa Vision Shield to the Helium Network with Educational videos showing typical Arduino users 
how to connect and use the Helium Network.






-----


**Code Repos of team of key applicant:**

The Final Product Github Link: [Maker100](https://github.com/hpssjellis/maker100)


The Final Product Video Playlist: [Youtube Maker 100 Videos](https://www.youtube.com/playlist?list=PL57Dnr1H_egv1FVzAcCZVeANJMs3Hta05)


The Final Product Library for the Arduino IDE: [portenta-pro-community-solutions](https://github.com/hpssjellis/portenta-pro-community-solutions)

My Github Profile: [Jeremy Ellis Github Profile](https://github.com/hpssjellis) 




----

**Project Details:**

- Background: The Arduino Portenta https://store.arduino.cc/usa/portenta-h7 is the new $103.40 USD "Pro" Arduino board with impressive abilities (easy Arduino programming of this dual core, 160 pin, Wifi, BLE, I2C and LiPo connector board.) especially when combined with the $63.00 USD LoRa Vision Shield https://store.arduino.cc/usa/portenta-vision-shield-lora  and the optional $45.99 USD Breakout board https://store.arduino.cc/usa/portenta-breakout. The Vision shield with 320px x 320px GRAYSCALE camera and dual microphones brings Machine Learning to DIY, Makers and Professional businesses alike. 

## Arduino Pro PortentaH7

![PortentaH7small](https://user-images.githubusercontent.com/5605614/132133468-9d787a43-3d0b-41f8-97f4-7bb5fa66680a.jpg)



## LoRa Vision Shield
This snaps to the back of the PortentaH7 using 2 x 80 pin high Density connectors.


![lora-vision-small](https://user-images.githubusercontent.com/5605614/132133504-dfbcf4fb-961d-4bc1-82bb-165a1d87c438.jpg)


## Optional BreakoutBoard

![image](https://user-images.githubusercontent.com/5605614/132133509-777da3cc-c121-416c-88ea-c8cba7a1ae94.png)







- Problem (as of May 2021): Unlike many LoRa capable boards the Portenta does not give direct access to the LoRa module, making most LoRa and LoRaWan example code useless. The Arduino MKRWAN library can connect to the TTN (TheThingsNetwork) in Europe but has some issues connecting in North America.  
- Problem to Solve: Helium connectivity in North America does not work with the present May 2021 Arduino examples. 
- Connecting is only the first step, simple sensors and actuator examples are also needed.

- Solution: I plan to simplify getting Portenta sensors and machine learning working on the Helium Network. 
- First with basic connectivity, then simplifying Cayenne MQTT server presentation of the uploaded data.
- (Update: Summer 2021) I have spent several months looking into solutions and now with recent improvements to the Arduino MKRWAN library I have 2 proven methods to connect to Helium in North America






-----

**Roadmap:**

| Milestone + Date | Deliverable | Summary | Cost |
| --- | --- | --- | --- |
|  MS#1 Spring 2021 | Research Arduino Portenta Pro Dual Core 160 pin microcontroller |     Done    [Generic Portenta Github](https://github.com/hpssjellis/my-examples-for-the-arduino-portentaH7)       |     $500 USD         |
|  MS#2  Summer 2021| Research LoRa and LoRaWan abilities for the Arduino Portenta Pro LoRa Vision Shield, using the Murata Module and the [GrumpyOldPizza](https://github.com/GrumpyOldPizza/ArduinoCore-stm32l0) Library |     Done    [Portenta Murata Module LoRa Control](https://github.com/hpssjellis/portenta-lora-murata-stm32lo)       |     $500 USD         |
|  MS#3  Summer 2021| Research LoRa and LoRaWan abilities for the Arduino Portenta Pro LoRa Vision Shield, using the [MKRWAN](https://github.com/arduino-libraries/MKRWAN) Arduino Library |     Done  [MKRWAN Relevant Issues](https://github.com/arduino-libraries/MKRWAN/issues?q=is%3Aissue+portenta)        |     $500 USD         |
|  MS#4    Fall 2021       |        Create Multiple Educational videos of connecting Sensors and Actuators to the Arduino Portenta        |     On Going  [Youtube here](https://www.youtube.com/watch?v=3E5KUT115xY&list=PL57Dnr1H_egv1FVzAcCZVeANJMs3Hta05&index=7)     |     $500 USD       |
|  MS#5    Fall 2021         |        Connect the Portenta to the Helium Network                                               |     On Going [ Code here](https://github.com/hpssjellis/portenta-pro-community-solutions/blob/main/examples/c-portenta-vision-shields/c-b-lorawan-specific/c-b-b-helium-cayenne-us915/c-b-b-helium-cayenne-us915.ino)        |     $1000 USD          |
|  MS#6    Fall 2021       |        Create Multiple Machine Learning Examples For The Arduino Portenta LoRa Vision Shields        |     On Going [ML Examples folder](https://github.com/hpssjellis/portenta-pro-community-solutions/tree/main/examples/e-portenta-machine-learning)    |     $1000 USD         |
|  MS#7    Fall 2021       |        Create Multiple Educational videos of Machine Learning with the Arduino Portenta and Vision Shields       |     Not Yet Started     |     $1000 USD         |
|  MS#8     Spring 2022         |         Create Multiple Educational videos of the multiple steps to connect the Arduino Portenta with LoRa Vision Shield to the Helium Network and how to extract useful Information from it           |     Not Yet Started      |    $1000 USD       |
|  MS#9     July 2022         |         Create a Github summary of all facets of Learning microcontroller sensors, actuators, machine Learning and how to send the information to the Helium Network      |     On Going [Maker100 Course](https://github.com/hpssjellis/maker100)     |    $500 USD       |
|  MS#10    August 2022       |        Make an Arduino Library of useful code and examples              |     On Going  [portenta-pro-community-solutions](https://github.com/hpssjellis/portenta-pro-community-solutions)  Arduino IDE Library      |    $500 USD         |
| --- | --- | --- | Total $7000.00 USD |



----

## Generic Links related to this Project

Maker100 Robotics Curriculum: [https://github.com/hpssjellis/maker100](https://github.com/hpssjellis/maker100)

Maker100 Video Playlist [https://github.com/hpssjellis/portenta-pro-community-solutions/blob/main/examples/a-portentaH7-examples/a-a-hello-blink/a-a-hello-blink.ino](https://github.com/hpssjellis/portenta-pro-community-solutions/blob/main/examples/a-portentaH7-examples/a-a-hello-blink/a-a-hello-blink.ino)


Twitter: [https://twitter.com/rocksetta](https://twitter.com/rocksetta)
                 
Website: [https://www.rocksetta.com/](https://www.rocksetta.com/ ) 
                
Machine Learning using TensorflowJS: [https://www.rocksetta.com/tensorflowjs/](https://www.rocksetta.com/tensorflowjs/)
   
## Older Links   
   
Youtube Arduino Playlist: [https://www.youtube.com/watch?v=bVIdH92dcqg&list=PL57Dnr1H_egtm0pi-okmG0iE_X5dROaLw](https://www.youtube.com/watch?v=bVIdH92dcqg&list=PL57Dnr1H_egtm0pi-okmG0iE_X5dROaLw)
                
Robotics Curriculum with Video Series:   [https://github.com/hpssjellis/particle.io-photon-high-school-robotics](https://github.com/hpssjellis/particle.io-photon-high-school-robotics)
                
Arduino Portenta Solutions: [https://github.com/hpssjellis/my-examples-for-the-arduino-portentaH7](https://github.com/hpssjellis/my-examples-for-the-arduino-portentaH7)

## Relevant Experience by Jeremy Ellis

I have taught coding for 30 years, taught robotics for 7 years, developed my own Robotics curriculum. Have a Chemistry Degree, An Education Degree and a Diploma in Counseling.  Taught myself Machine learning, am an Edge Impulse Ambassador https://www.edgeimpulse.com/ Have a class set of Arduino Portenta, with LoRa Vision Shields and Breakout boards for teaching Robotics during the next few years. 









