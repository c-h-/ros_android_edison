# Robot Operating System on Intel Edison streaming Android Sensor Data
This repository links all the tools needed to get an Intel Edison running Robot Operating System and subscribing to sensor readings from a network of Android devices.

## Guide
- `edison_install_ubilinux` walks you through installing Ubilinux onto Edison, an OS that can handle ROS 
- `edison_install_ros` walks you through installing Robot Operating System on an Intel Edison running Ubilinux
- `android_core` contains all the setup necessary to develop ROS-enabled Android apps
- `android_subscriber` contains code to run on the Edison concurrently with the ROS master node (e.g. run the subscriber in here after you start `roscore`)
