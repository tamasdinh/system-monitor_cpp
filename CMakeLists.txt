cmake_minimum_required(VERSION 3.14)
project(19_System_monitor_CPP)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(19_System_monitor_CPP
        constants.h
        main.cpp
        Process.h
        ProcessContainer.h
        ProcessParser.h
        SysInfo.h
        util.h)
