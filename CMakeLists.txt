cmake_minimum_required(VERSION 3.10)

project(
            Hello_World
            LANGUAGES CXX   
)

add_executable( ${PROJECT_NAME} "${CMAKE_CURRENT_SOURCE_DIR}/src/main.cc" )