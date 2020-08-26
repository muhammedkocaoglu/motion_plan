cmake_minimum_required(VERSION 2.8.3)
project(motion_plan)


find_package(catkin REQUIRED COMPONENTS
  gazebo_msgs
  geometry_msgs
  rospy
  sensor_msgs
  std_msgs
  gazebo_ros
)


include_directories(
  ${catkin_INCLUDE_DIRS}
)


