# UAV for Precision Agriculture in a Modular Approach
This repository encloses my research work on UAV for precision agriculture that was published as a conference paper at IEEE UPCON 2020. The project uses an autonomous UAV, guided by the open source QGC app, and is capable of analysing plant health, and identifying insects and weeds in the field. The development is described in detail piecewise according to the phases in SDLC. 

## Introduction to the Project

* With the advancement in aerial robotics, the technology can be modified and developed to aid farmers in agriculture. 
* Common field problems involve analysing Plant Health status, and the presence of insects and weeds in the field. 
* Image processing tools, and concepts of machine learning are invoked and incorporated in the onto the UAV wherein a microcomputer (Raspberry Pi) is mounted.
* This project uses Raspberry Pi - NOIR Camera to get Near Infrared Spectrum for plant health analysis. Real time feed is sent to flask application server
* Calculations are done based on the NIR spectrum data to compute the Normalised Difference Vegetation Index for plants in the farm, and the health status is presented to the user on the flask application server. 
