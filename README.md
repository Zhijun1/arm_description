# arm_description
A modified 6 DoF arm urdf file

This is a modified 6 DoF arm with a reference of yao62995's AS_6Dof_Arm. This repository significantly reduced the orignial urdf, and only keep its urdf description directory for simplicity.

You need to git clone it into your ROS catkin src directory, and catkin_make and then run it:

$ cd your_catkin_space/src
$ git clone this_repository_in_github
$ cd .. && catkin_make
$ source ./devel/setup.bash
$ roslaunch urdf_tutorial display.launch model:='./src/rarm_description/urdf/arm_description.urdf'


