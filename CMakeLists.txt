cmake_minimum_required(VERSION 3.11)

project(
    Project_Name
    VERSION 0.1.0
    DESCRIPTION "Project Description"
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 11)

include_directories(include)

add_executable(main src/main.cpp)