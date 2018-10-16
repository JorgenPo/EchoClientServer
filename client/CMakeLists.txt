project(EchoClient)

set(CMAKE_CXX_STANDARD 17)

file(GLOB SOURCES src/*.cpp src/*.h)

add_executable(EchoClient ${SOURCES} ${COMMON_SOURCES})