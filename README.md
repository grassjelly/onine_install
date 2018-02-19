# onine_install [![Build Status](https://travis-ci.org/grassjelly/onine_install.svg?branch=master)](https://travis-ci.org/grassjelly/onine_install)

## Installation
This will install all required packages to build Onine robot including:
- Linorobot package
- Navigation Stack
- MoveIt
- Robotic Arm's firmware
- Kinect ROS driver

You need to pass one argument to the install file where:

base = The type of robot base you want to use for Onine. Valid arguments are 2wd, 4wd, ackermann, and mecanum.

    $ ./install <base>

