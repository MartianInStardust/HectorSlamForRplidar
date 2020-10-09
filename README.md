# HectorSlamForRplidar

Modified HectorSlam lib for ROS Noetic to use. 
Migrated some Qt lib from Qt4 to Qt5 
Issues with hector slam when odom data is not present 
1. Sudden yall change problem: 
Sudden turn will ruin the map 
2. Corridor probelm: 
Hector slam think the robot is not moving when laser scan datas are almost the same at long corridor . 
This problem is stated clearly on ros answers, and because hector slam is not using odometer (exclude roll & pitch), 
the problem can not be solved 
