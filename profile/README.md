# CyberBot

CyberBot is a two-wheeled balancing robot based on a five-bar linkage. Its hardware is built around a Raspberry Pi 4 and a custom HAT. The HAT hosts an ESP32-S3 that handles the low-level balancing task. It communicates with the ICM-20948 IMU and six Xiaomi CyberGear motors.

The Holybro PM03D power module distributes power to the system. The ESP32 runs a micro-ROS node that communicates over a serial connection with ROS 2 on the Raspberry Pi.

A Gazebo simulation is available, but remains a work in progress. The project is not yet complete; additional repositories will be published and documented over time.

The central documentation takes place in the [Wiki](https://github.com/cybergear-robotics/.github/wiki)
