cmake_minimum_required(VERSION 3.5)
project(carter_test)

find_package(ament_cmake REQUIRED)

install(DIRECTORY
  launch
  params
  Map
  rviz2
  DESTINATION share/${PROJECT_NAME})

ament_package()
