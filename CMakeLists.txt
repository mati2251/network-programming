cmake_minimum_required(VERSION 3.25)
project(network-programming)

set(CMAKE_CXX_STANDARD 20)

add_executable(client client/main.cpp)
add_executable(server-tcp server-tcp/main.cpp)
add_executable(server-udp server-udp/main.cpp)
add_executable(client-udp client-udp/main.cpp)
add_executable(translate-dns-old translate-dns-old/main.cpp)
add_executable(client-tcp-dns client-tcp-dns/main.cpp)
