cmake_minimum_required(VERSION 2.8.3)
project(my_nav_test)

# add_compile_options(-std=c++11)

find_package(catkin REQUIRED COMPONENTS
  map_server
  move_base
  gazebo_ros
  turtlebot_gazebo
  turtlebot_navigation
  robot_state_publisher
  nodelet
  roscpp
  rospy
)

