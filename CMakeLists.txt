cmake_minimum_required(VERSION 3.25)
project(network-programming)

set(CMAKE_CXX_STANDARD 20)

add_executable(client client/main.cpp)
add_executable(server-tcp server-tcp/main.cpp)
