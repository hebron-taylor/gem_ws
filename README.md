# gem_ws
A catkin workspace for the development of UIUC's autonomous GEM Golf Car gazebo simulation environment 



##Requirements
* Ubuntu 16.04
* Gazebo 8+
* ROS Kinetic 

##Current Modules
* Sensor Fusion - Combines LiDAR and Camera data
    roslaunch gemulator sensorFusion.launch
    python mp2.py (gemulator/src/sensorFusion)
