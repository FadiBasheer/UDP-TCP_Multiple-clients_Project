cmake_minimum_required(VERSION 3.21)
project(UDP_server C)

set(CMAKE_C_STANDARD 11)

add_executable(UDP_server
        server.c)
