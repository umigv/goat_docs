# phidgets_imu

## Overview
ROS driver for phidgets imu, grabs raw data from accelerometer, gyrometer, and magnetometer 
It reads the data in the NED coordinate system

## Installation
Install straight in ROS catkin_ws, follow installation and depencies in: 
[https://github.com/ros-drivers/phidgets_drivers](https://github.com/ros-drivers/phidgets_drivers) 

## Details
ROS Node: phidgets_imu_node 
Pkg Name: phidgets_imu 
No params  

ROS topics:
- /imu/data_raw: sensor_msgs/Imu
- /imu/mag: sensor_msgs/MagneticField.msg 

## Build

## Run
 
## Known Issues

## More Resources
[https://wiki.ros.org/phidgets_drivers](https://wiki.ros.org/phidgets_drivers) 
