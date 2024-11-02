cmake_minimum_required(VERSION 2.8.3)
project(reactive_robot_sim)

find_package(catkin REQUIRED)

catkin_package(
    CATKIN_DEPENDS
        turtlebot3
        turtlebot3_simulations
)
