cmake_minimum_required (VERSION 3.5)

project(BehaviorPlanner)

add_definitions(-std=c++11)

set(CXX_FLAGS "-Wall")
set(CMAKE_CXX_FLAGS, "${CXX_FLAGS}")

set(sources main.cpp cost.cpp road.cpp vehicle.cpp)

add_executable(BehaviorPlanner ${sources})
