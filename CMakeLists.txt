cmake_minimum_required(VERSION 3.12)
project(EchoApp)

file(GLOB COMMON_SOURCES common/*.h common/*.cpp)
include_directories(common)

add_subdirectory(client)
add_subdirectory(server)