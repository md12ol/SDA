cmake_minimum_required(VERSION 3.16.5)
project(SDA)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_BUILD_TYPE "Release")

add_executable(SDATester
        main.cpp
        SDA.cpp
        SDA.h)