# SMART AGRICULTURE USING IOT
## AN EXPERIENTIAL LEARNING PROJECT REPORT

Department of Computer Science and Engineering  
C. V. RAMAN GLOBAL UNIVERSITY  
Bhubaneswar - Odisha - India  

---

### CONTENTS

1. [TEAM MEMBER DETAILS](#team-member-details)  
2. [CERTIFICATE](#certificate)  
3. [DECLARATION](#declaration)  
4. [ACKNOWLEDGEMENT](#acknowledgement)  
5. [INTRODUCTION](#introduction)  
6. [ABSTRACT](#abstract)  
7. [PROPOSED SYSTEM](#proposed-system)  
    - System Overview
    - Soil Moisture Sensor
    - DHT 11 (Digital Humidity Temperature Sensor)
    - Ultrasonic Sensor
    - Relay
    - Motor
    - ESP8266 Node MCU
    - Arduino IDE
    - Blynk Application
    - Sketch Block Diagram
8. [RESULT](#result)
9. [ADVANTAGES](#advantages)
10. [LIMITATIONS](#limitations)
11. [FUTURE SCOPE](#future-scope)
12. [CONCLUSION](#conclusion)
13. [REFERENCES](#references)

---

### TEAM MEMBER DETAILS

| NAME                  | REG. NUMBER |
|-----------------------|-------------|
| Sudhansu Kumar        | 2201030100  |
| Mangal Maharana       | 2101020767  |
| Anurag Raj            | 2101020762  |
| Maitrijeet Behera     | 2101020740  |
| Aman Ujwal Toppo      | 2201030141  |
| Rishav Kumar          | 2101020766  |
| Pratyush Ranjan Mahanta | 2201030133 |

---

### CERTIFICATE

This is to certify that the project report entitled “SMART AGRICULTURE USING IOT” submitted by our group members to the C.V. Raman Global University in partial fulfillment for the case study/experiential learning is a Bonafede record of project work carried out by them under our supervision.

The contents of this report, in full or in parts, have not been submitted to any other Institution or University for the award of any degree or diploma.

Signature-

---

### DECLARATION

We declare that this project report titled “SMART AGRICULTURE USING IOT” submitted in partial fulfillment of The case study/experiential learning is a record of original work carried out by us under the supervision of Dr, Raj Vikram, and has not formed the basis for the award of any other degree or diploma, in this or any other Institution or University. In keeping with the ethical practice in reporting scientific information, due acknowledgements have been made wherever the findings of others have been cited.

---

### ACKNOWLEDGEMENT

We have taken efforts in this project. However, it would not have been possible without the kind support and help of many individuals. We would like to extend my sincere thanks to all of them.

We are highly indebted to Dr. Raj Vikram for his guidance and constant supervision as well as for providing necessary information regarding the project and also for her support in completing the project. His constant guidance and willingness to share his vast knowledge made us understand this project and its manifestations in great depths and helped us to complete the assigned tasks on time.

We would like to express our gratitude towards our parents and other friends for their kind cooperation and encouragement which helped us in completion of this project.

Our thanks and appreciation also go to our colleagues in developing the project and people who have willingly helped us out with their abilities.

---

### INTRODUCTION

Since agriculture is the primary source of food grains and other raw materials, it is the foundation of human existence. In the case of India, agriculture is both the backbone and a key component of the economies of developing nations. People can find massive employment prospects using it. The expansion of the agriculture sector is essential for the nation's economic development. Sadly, a lot of farmers continue to grow crops with low yields due to the old, traditional methods. However, yields have increased when the innovations were put into practice and automated technologies took the position of humans.

Therefore, in order to increase yield, the agricultural sector must employ new technologies. There has been a lot of research and development in the field of agriculture about new IoT technologies. The production of food grains needs to be increased in the current times. A cloud-connected technology facilitates the optimization of crop productivity, assisting with routine agricultural operations and providing real-time monitoring.
Connected equipment has several Wi-Fi connections, which aid in the monitoring and management of electronic machinery to support farmers in crop field analysis and optimal performance. Today, many farmers are able to monitor their land, measure temperature, and moisture content with efficiency thanks to the use of sensor devices and other automated electronics equipment.

---

### ABSTRACT

In our nation, agriculture has long been the main industry or source of revenue. However, lately, because of the erratic weather and the lack of suitable land has made cultivation difficult. As a result, both our nation and the majority of other nations now seriously worry about food security. In order to overcome this, we use the Internet of Things (IoT) in Smart Agriculture systems to increase the sector's productivity and operational efficiency. This system's feature is the development of a sensor-based microcontroller system that can monitor temperature, humidity, moisture, and even the potential movement of animals that could destroy agricultural resources. If there is any disparity, the system will send out an alert message using Wi-fi/3G/4G module to the farmers’ smartphone. Its low cost makes it affordable for all farmers, and its many qualities make it potentially useful in locations with restricted water supplies.

In order to gather data on soil moisture, temperature, and humidity as well as to operate a manually operated motor to distribute water in the field based on demand and make decisions appropriately, we are putting forth an effective and affordable sensor network technology in this project.

---

### PROPOSED SYSTEM

#### SYSTEM OVERVIEW

The Smart Agricultural system is an increasing trend in our day-to-day life. As technology has advanced, agriculture has benefited from the newest methods and trends.
The connectivity provided by smart agriculture through the use of current Wi-Fi technology is one of its main advantages. 

#### SOIL MOISTURE SENSOR

A sensor that measures the amount of moisture in a field is called a soil moisture sensor. The LED in the field will glow when the water level in the Blynk app is low, and it won't shine when the water level is high.

#### DHT 11 (Digital Humidity Temperature Sensor)

Digital Humidity Temperature Sensor (DHT11) is comprised of a thermistor and a humidity sensing component for sensing the temperature. This humidity sensing capacitor has two electrodes with a substrate which contains moisture as a dielectric between them.

#### ULTRASONIC SENSOR

The HC-SR04 ultrasonic sensor uses a sound burst to measure the distance to an item. There are two ultrasonic transducers in it.

#### RELAY

Relays are employed as electrical switches, and the electronic schematic of one is shown in the figure below. In this project, a relay is employed to activate the water pump in the event that the field's water level drops.

#### MOTOR

A Mini Micro Submersible Water Pump is depicted below. The motor runs on DC 3-6V
