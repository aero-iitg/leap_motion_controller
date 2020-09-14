# leap_motion_controller
Control a Drone with leap motion controller to detect gesture and control a drone

## The software packages used were :
- 1.Leap motion Ros (https://github.com/warp1337/rosleapmotion)
- 2.ROS Python package (if not installed, type command: pip3 install rospy )
- 3.Gazebo for simulation 
- 4.PX4 Firmware for ros simulation (https://github.com/PX4/Firmware)
 
## Hardware Used:
  - Pixhawk 4 flight controller
  - Leap motion hand gesture detector
 
## How to use it :
```bash
roslaunch custom.launch
python3 takeoff.py
python3 leap.py
```
The controller was unstable in real world so it was mostly used in simulation.
