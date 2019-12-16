The test package implements simulation through turtlebot simulators for usv navigation stack

Run:
  roslaunch my_nav_test turtlebot_world.launch
  roslaunch my_nav_test amcl_demo_copy.launch
  roslaunch my_nav_test view_navigation.launch

Before run:
Turtlebot simulator and nav_navigation package are necessary
Turtlebot simulator: 
  sudo apt-get install ros-[ROS_VERSION]-turtlebot*
nav_navigation: 
  git clone https://github.com/wangzhao9562/usv_navigation.git
  catkin_make or catkin build
