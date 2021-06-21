sudo apt install ros-melodic-joint_state_publisher-gui

source /home/lisandro/catkin_ws/devel/setup.bash

rospack find mrm_description

rosrun xacro xacro.py /home/lisandro/catkin_ws/src/mrm_description/urdf/mrm.xacro

check_urdf mrm.xacro

Luego construir el paquete con catkin_make
