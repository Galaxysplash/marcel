cmake_minimum_required(VERSION 3.20)
project(marcel)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

file(GLOB SRC "src/*.cpp")


add_executable(${PROJECT_NAME})

target_sources(${PROJECT_NAME} PRIVATE ${SRC})