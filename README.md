# dccomms_ros_pkgs
ROS packages with network simulation utilities. The NS3 library is used, which has been integrated as a git submodule.

### Dependencies
The C++ compiler must support C\+\+11 and C\+\+14 (tested in Ubuntu 18.04).

### Install and Build
Clone this repository into the src folder of your catkin workspace with the *--recursive* option and build the workspace:
```bash
~/catkin_ws/src$ git clone --recursive https://github.com/dcentelles/dccomms_ros_pkgs.git
~/catkin_ws/src$ cd ..
~/catkin_ws$ catkin_make
```
### Using the library
Check the Wiki pages for more info.

[![Build Status](https://travis-ci.org/dcentelles/dccomms_ros_pkgs.svg?branch=master)](https://travis-ci.org/dcentelles/dccomms_ros_pkgs)

