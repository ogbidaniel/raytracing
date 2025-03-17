cmake_minimum_required(VERSION 3.10)

project(RayTracingTutorial)

# Specify C++ standard (you can adjust to 14, 17, etc., if you prefer)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Create an executable from main.cpp
add_executable(rtiow main.cpp)