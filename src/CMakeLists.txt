cmake_minimum_required(VERSION 3.27)
project(cube C)

set(CMAKE_C_STANDARD 11)

include_directories(..)
include_directories(.)

add_executable(cube
        screen.h)
