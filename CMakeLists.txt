cmake_minimum_required(VERSION 3.10)
#set the project name
project(Cs2_Claculator)
#add the excutable
add_executable(calculator test.cpp calculator.cpp)
#include Directories
include_directories(${PROJECT_SOURCE_DIR})
#set C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)