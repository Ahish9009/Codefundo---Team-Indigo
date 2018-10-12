# Codefundo---Team-Indigo
## Team Indigo's idea for Code.Fun.Do

### Introduction

Our idea is divided into two parts:
* A Drone System
* A Hub System

#### Target Disasters 
  * Earthquakes, Floods, Tsunamis, Landslides, etc.

### Drone System

We plan to build a network of drones in order to help locate and distribute resources among the disaster-stricken people. It will also be used as a real time source of data from the affected region.

* Drone Features
  * GPS Enabled
  * 3-Axis Camera
  * Connectivity to Azure Cloud
  * Connectivity to Base
  * Low to Medium sized Payload

#### Working

 - Drones will be deployed across the disaster-stricken region in an optimal manner. Each drone will be connected to the base,    ie. the data center(where all the data collected by the drone will be sent for processing). <br /><br />
 - Each drone will collect data in real time by scanning the environment with the camera, and send it to the base for processing. The processed data will then again be used to reroute the drones and assign tasks to them. The drone will also implement a system to recognize people's locations, providing rescue workers with invaluable information on where to concentrate their rescue efforts. <br /><br />
 - We also plan to try to empower the drone to recognize blocked/unsafe roads to allow the rescue workers to reach the affected sites using the most optimal routes. 
 - At times, the drones maybe assigned to carry ration supplies to and from places. 
 
#### Implementation

 - The above mentioned features will be implemented by using Microsoft Azure's Cognitive Services and Custom Vision API, along with a Maps API and GPS. The camera will be used to take and send images from the drone to the base for analysis.
 - The SOC on board will be used to send instructions to the drone as well as to monitor it's status.
 - A slight modification will be made to the drone in order to enable it to carry payloads.
 

