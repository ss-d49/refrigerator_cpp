cmake_minimum_required(VERSION 3.17)
project(untitled)

set(CMAKE_CXX_STANDARD 20)

add_executable(untitled main.cpp ObjectIO.cpp foodItem.cpp fridgeInventory.cpp main.h)