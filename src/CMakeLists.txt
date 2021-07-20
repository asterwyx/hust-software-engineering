cmake_minimum_required(VERSION 3.17)
project(monopoly)
set(CMAKE_CXX_STANDARD 14)
include_directories(.)

add_executable(monopoly
        main.cpp
        cmdline.cpp
        cmdline.h
        map.cpp
        map.h
        player.cpp
        player.h)
