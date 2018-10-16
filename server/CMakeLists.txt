project(EchoServer)

set(CMAKE_CXX_STANDARD 17)

file(GLOB SOURCES src/*.cpp src/*.h)

add_executable(EchoServer ${SOURCES} ${COMMON_SOURCES})

find_package(Threads REQUIRED)

target_link_libraries(EchoServer ${CMAKE_THREAD_LIBS_INIT})