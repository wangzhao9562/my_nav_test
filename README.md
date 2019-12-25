# my_nav_test

The test package implements the simulation of usv navigation stack through turtlebot simulators.

## Prepare  
sudo apt-get install ros-kinetic-turtlebot*  
git clone https://github.com/wangzhao9562/usv_navigation.git  
cd ~/catkin_ws  
catkin_make  
source devel/setup.bash  

## Run    
roslaunch my_nav_test turtlebot_world.launch  
roslaunch my_nav_test amcl_demo_copy.launch  
roslaunch my_nav_test view_navigation.launch  

