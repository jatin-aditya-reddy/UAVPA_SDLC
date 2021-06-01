# Requirements
## Introduction
* Hardware knowledge to develop a Drone (Quad-copter preferably), including soldering, interconnects on Powerdistribution Board, etc.
* Camera and Mini-Computer (Raspberry Pi) Mounts on the drone, and the payload lift capacity calculated to meet the weight constraints for safe flight
* Software Application to process the captured Near Infrared Spectrum on the NoIR Camera. 
* Development of the Flask application server to present the realtime feed to the system.
* Alternate Mount for an action camera to record video in SD/HD for insect and weed identification.
* Knowledge of QGroundControl (Open Source Application) integration to the flightcontroller (Pixhawk PX4) and manual operations (for emergencies and failsafe)

## Research

* Existing research (Cited below and in the conference paper, (link: https://ieeexplore.ieee.org/abstract/document/9376521), suggest the practicality of the product (if developed)
* It is possible to capture images and calculate the NIR band to estimate NDVI, this can be incorporated for a stream of images, i.e. video with defined FPS (Frames Per Second)
* Autonomous Aerial Vechiles are app-guided i.e. (Via PC or Smartphones), and the same technology can be incorporated with the proposed idea to help farmers operate such a complex system with ease.
* Drone Stability and product cost has been an industrial challenge owing to the physical complexities in the design.

Here are some reference papers that were vital for the development of this project.

1. Rangel Daroya, Manuel Ramos, “NDVI image extraction of an agricultural land using an autonomous quad-copter with a filter-modified camera” International Conference on Control System, Computing and Engineering (ICCSCE), 2017
2. J. L. E. Honrado, D. B. Solpico, C. M. Favila, E. Tongson, G. L. Tangonan, N. J. C. Libatique, "UAV imaging with low-cost multispectral imaging system for precision agriculture applications", Global Humanitarian Technology Conference (GHTC) 2017 IEEE, pp. 1-7, 2017
3.	Pest Detection on UAV Imagery using a Deep Convolutional Neural Network *Yacine Bouroubi, Pierre Bugnet, Thuy Nguyen-Xuan, Claire Gosselin, Carl Bélec, Louis Longchamps and Philippe Vigneault In Proceedings of the 14th International Conference on Precision Agriculture (unpaginated, online). Monticello, IL: International Society of Precision Agriculture

## Cost and Features Breakdown

**_Cost_**

* The software aspect of the system is free of cost, as it uses open source software and developed software from research accessible to everyone. 
* The hardware used in this research prototype involves basic drone components, Raspberry Pi 3B, Pixhawk PX4 FC, NOIR RPi camera and an action camera (SD/HD), the total cost is approxmiately INR 53000/- which is subject to change as per fluctuating market prices day by day. 

**_Features_**

The features of the system are:
1. Autonomous Flight
2. Self Stablization (Hover)
3. Altitude Hold (Alt_Lock)
4. RTL (Return to launch i.e. failsafe)
5. Mobile App Control
6. Flight time ~ 20 minutes
7. Plant health analysis
8. Insect and weed detection

## Defining the System
![System Design](https://user-images.githubusercontent.com/84840612/120294274-a9f98980-c2e3-11eb-8c09-0031c0e1b21f.png)

## SWOT Analysis
![SWOT](https://user-images.githubusercontent.com/84840612/120296662-f9d95000-c2e5-11eb-9587-32cc925b0848.jpg)

# 4W's and 1'H

**Who:**



