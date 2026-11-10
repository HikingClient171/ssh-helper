cmake_minimum_required(VERSION 4.5.0)
project(ssh-helper VERSION 0.1.0 LANGUAGES CXX C)

add_subdirectory("src/server")
add_subdirectory("src/client")

include_directories(${PROJECT_NAME} PRIVATE
    "../include"
)
