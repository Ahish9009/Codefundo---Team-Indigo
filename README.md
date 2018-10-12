# Code.Fun.Do++ | Team-Indigo
## Team Indigo's Idea

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
  * Onboard SoC 

#### Working

 - Drones will be deployed across the disaster-stricken region in an optimal manner. Each drone will be connected to the base,    ie. the data center(where all the data collected by the drone will be sent for processing). 
 - Each drone will collect data in real time by scanning the environment with the camera. The processed data from the base will then again be used to reroute the drones. The drone will also implement a system to recognize people's locations, providing rescue workers with invaluable information on where to concentrate their rescue efforts.
 - We also plan to try to empower the drone to recognize blocked/unsafe roads to allow the rescue workers to reach the affected sites using optimal routes. 
 - At times, the drones maybe assigned to carry ration supplies to and from places. 
 
#### Implementation

 - The above mentioned features will be implemented by using Microsoft Azure's Cognitive Services and Custom Vision API, along with a Maps API and GPS. The camera will be used to take and send images from the drone to the base for analysis.
 - The SOC on board will be used to send instructions to the drone as well as to monitor it's status.
 
### Hub System

To complement the Drone system, a hub system will be implemented to keep accounts of the available resources and suggest future expenditures based on people's needs. 
 
* Hub Features
  * Support for a basic DBMS
  * Structured Addressing of Commodity Requests
  * Centralized System for the Authorities to Buy Basic Commodities

#### Working

 - The hub will provide a common link between various service providers and the authorities. The service providers will then be able to list out of their services and goods along with the price. This will provide the authorities a hassle-free and convenient method to purchase miscellaneous goods and services. 
 - Rescue workers on site will be able to put up requests for goods, that are required at their location, on a common platform. The hub will have categories for the type of goods required such as food, water, etc. 
 - The hub will then push notifications to the required authorities and resellers that sell the particular commodity.
 - We also plan to incorporate the information from the drone system to prioritize the needs of people in a certain region. 
 
 #### Implementation
 
 - We plan to use the Azure SQL Database System in the backend.
 - Queries will be pushed to the database in order to manipulate the data.
 - A UI will be developed to display information and accept queries.
 
 #### Possible Updates
 - Decentralizing the resource sharing platform to enable transparency, establish trust among donors, identify demand and allocate resources effeciently.
