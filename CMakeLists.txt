cmake_minimum_required(VERSION 3.21)

project(OrangeMod)

set(CMAKE_CXX_STANDARD 20)

add_library(${PROJECT_NAME} SHARED
    src/main.cpp
)

setup_geode_mod(${PROJECT_NAME})
