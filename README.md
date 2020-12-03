# GeekKKOKKO
Autonomous mobile robot project using lane detection.

# Requirements
- Ubuntu 16.04
- ROS Kinetic
- [realsense2_camera](https://github.com/IntelRealSense/librealsense)
- [HLDS HLS-LFCD-LDS](https://github.com/ROBOTIS-GIT/hls_lfcd_lds_driver)
- [rosserial](http://wiki.ros.org/rosserial_arduino/Tutorials/Arduino%20IDE%20Setup)

# Usage
```
roscore

// Run GeekKKOKKO
roslaunch GeekKKOKKO geekble_main.launch

// Find HSV color
roslaunch GeekKKOKKO geekble_rangeHSV.launch

// Find BGR color
roslaunch GeekKKOKKO geekble_rangeBGR.launch
```
20201203