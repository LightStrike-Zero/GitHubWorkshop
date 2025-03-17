# Explore this file for yourself, what is Cmake?
cmake_minimum_required(VERSION 3.28)
project(GitHub)

set(CMAKE_CXX_STANDARD 17)

set(SOURCES
        main.cpp
)

add_executable(${PROJECT_NAME} ${SOURCES})

