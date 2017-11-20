# Specify the minimum version for CMake
cmake_minimum_required(VERSION 2.8)

# Project's name
project(FreeAI)

# Set the output folder where your program will be created
set(CMAKE_BINARY_DIR bin)

set(PROJECT_SOURCE_DIR src)

# The following folder will be included
include_directories(${PROJECT_SOURCE_DIR})

#Can manually add the sources using the set command as follows:
set(SOURCES

    ${PROJECT_SOURCE_DIR}/main.cpp
    ${PROJECT_SOURCE_DIR}/individual.cpp
    ${PROJECT_SOURCE_DIR}/population.cpp
)
 
file(GLOB SOURCES "${PROJECT_SOURCE_DIR}/*.cpp")

add_executable(FreeAI ${SOURCES})
