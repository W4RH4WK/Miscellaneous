cmake_minimum_required(VERSION 3.16)
project(serial LANGUAGES CXX)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
set(CMAKE_CXX_STANDARD 17)

add_executable(main src/main.cpp)
