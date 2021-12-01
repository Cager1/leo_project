# leo_project
Leo drive system

# How to run


cd ~/catkin_ws

source devel/setup.bash
r
oslaunch leo_drive spawn_leo.launch

New terminal---

cd ~/catkin_ws

source devel/setup.bash

rosrun leo_drive controller.py

# If controller.py wont run you have to make it an executable

cd ~/catkin_ws/src/leo_project/leo_drive/script

chmod +x controller.py
