Project:
Helium Arduino Portenta Lora Vision Shield Tutorials for Non-Engineers
Note: I have reduced the scope of this grant and removed the Sensor/Actuator and Machine Learning component as that may be better suited to a follow up grant next year.

Elevator Pitch:
The Helium People's Network needs everyday people to be able to use both the Hotspots and their own Devices. In my opinion only big companies with Mechatronic Engineers using ESP32's are able to create products that effectively use HNT.
I believe the network's success is centered on many people being able to make LoRaWan low power long distance solutions for their family and small business needs. The simplicity of the Arduino products is legendary and the Portenta is a beast, with it's dual core, 160 pin base and shields for Vision, Microphone, SD Card, Ethernet and LoRaWan. The PortentaH7 is the perfect choice for the technology capable Helium Hotspot owner.
I have the unique ability to simplify complex technology and the teaching experience to create a base set of tutorials to allow anyone to use the Helium Network with the Arduino PortentaH7 to its full potential.
What it is all about:
Here I show my Bobcat Miner beside an Arduino Portenta with the LoRa Vision Shield attached using the 2 x 80 pin attachments and a 915 MHz antenna powered by a regular cell phone charger. (LiPo or coin cell options on the large breakout board option are not shown)


Total Fiat/HNT ask:
$4,500.00 USD to connect the LoRaWan Arduino PortentaH7 with the LoRa Vision Shield to the Helium Network and to document the process on the Helium Docs including how to use the MQTT servers and Helium Console that are an integral part of the Helium data collection techniques.

Code Repos of team of key applicant:
The Final Product Github Link: Maker100
The Final Product Video Playlist: Youtube Maker 100 Videos
The Final Product Library for the Arduino IDE: portenta-pro-community-solutions
My Github Profile: Jeremy Ellis Github Profile

Project Details:
Background: The Arduino Portenta https://store.arduino.cc/usa/portenta-h7 is the new $103.40 USD "Pro" Arduino board with impressive abilities (easy Arduino programming of this dual core, 160 pin, Wifi, BLE, I2C, UART, SPI, Coincell and LiPo connector breakout board.). The Portenta becomes especially powerful when combined with the $63.00 USD LoRa Vision Shield (LoRaWan- Helium Connectivity, 320x320 GRAYSCALE camera, microphone, sd card, JTAG) https://store.arduino.cc/usa/portenta-vision-shield-lora and the optional $45.99 USD Breakout board https://store.arduino.cc/usa/portenta-breakout. 
Arduino Pro PortentaH7

LoRa Vision Shield
This snaps to the back of the PortentaH7 using 2 x 80 pin high Density connectors.

Optional BreakoutBoard, note the Vision shields can still snap to the back of the breakout board!

Problem
Problem (as of May 2021): Unlike many LoRa capable boards the Portenta does not give direct access to the LoRa module, making most LoRa and LoRaWan example code useless. The Arduino MKRWAN library can connect to the TTN (TheThingsNetwork) in Europe but has some issues connecting in North America.
Problem to Solve: Helium connectivity in North America does not work with the present May 2021 Arduino examples.
Solution: I plan to simplify getting the Portenta working on the Helium Network.
First with basic connectivity, then by simplifying how to use Cayenne connectivity to multiple MQTT servers which are needed to be able to present the uploaded data.
(Update: Summer 2021) I have spent several months looking into solutions and now with recent improvements to the Arduino MKRWAN library I have 2 proven methods to connect to Helium in North America


Updated Roadmap:
Milestone + Date                                    
Deliverable
Summary
Cost                   
MS#1 (Research) August  2021
Research Arduino Portenta Pro Dual Core 160 pin microcontroller. Research LoRa and LoRaWan abilities for the Arduino Portenta Pro LoRa Vision Shield, using the Murata Module and the GrumpyOldPizza Library. Research LoRa and LoRaWan abilities for the Arduino Portenta Pro LoRa Vision Shield, using the MKRWAN Arduino Library
Done Generic Portenta Github,  Portenta Murata Module LoRa Control, MKRWAN Relevant Issues

$1,500.00 USD
MS#2 (The Build) February 2022
Connect the Portenta to the Helium Network. Create several examples (code and/or notes/images) of sending data on the Helium network using the multiple MQTT methods. Simplify Open Source code examples. PR to Arduino MBED_core repository of  the main Helium Example.
On Going c-b-b-helium-cayenne-us915.ino, c-b-lorawan-specific    Arduino Github https://github.com/arduino/ArduinoCore-mbed
$2,0$1,500.00 USD
MS#3 ( The Docs) August 2022
Test introducing the above code to people with different levels of technological skills and make changes as appropriate. Update my maker100 site with explained examples of how to connect to the Helium network.  Send PR requests to the Helium docs to inform a wider Helium audience of how to use the Arduino Portenta using HNT.
Not Yet Started helium/docs
$1,500.00 USD
---
---
---
Total $5,000.00 USD



Generic Links related to this Project
Maker100 Robotics Curriculum: https://github.com/hpssjellis/maker100
Maker100 Video Playlist https://github.com/hpssjellis/portenta-pro-community-solutions/blob/main/examples/a-portentaH7-examples/a-a-hello-blink/a-a-hello-blink.ino
Twitter: https://twitter.com/rocksetta
Website: https://www.rocksetta.com/
Older Links
Youtube Arduino Playlist: https://www.youtube.com/watch?v=bVIdH92dcqg&list=PL57Dnr1H_egtm0pi-okmG0iE_X5dROaLw
Robotics Curriculum with Video Series: https://github.com/hpssjellis/particle.io-photon-high-school-robotics
Arduino Portenta Solutions: https://github.com/hpssjellis/my-examples-for-the-arduino-portentaH7
Machine Learning using TensorflowJS: https://www.rocksetta.com/tensorflowjs/
Relevant Experience by Jeremy Ellis
I have taught coding for 30 years, I have taught robotics for 7 years, and developed my own Robotics curriculum. I have a Chemistry Degree, An Education Degree and a Diploma in Counseling. I teach High School Technology including:Robotics, Coding, Animation and 3D Printing. I taught myself Machine learning. I am an Edge Impulse Ambassador https://www.edgeimpulse.com/ . I have a class set of the Arduino Portenta, with LoRa Vision Shields and Breakout boards for teaching Robotics during the next few years.









