cmake_minimum_required(VERSION 3.23)
project(leveldbdemo)

set(CMAKE_CXX_STANDARD 14)

link_libraries(pthread)
link_libraries(leveldb)
add_executable(leveldbdemo main.cpp)
