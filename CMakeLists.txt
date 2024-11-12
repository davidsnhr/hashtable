cmake_minimum_required(VERSION 3.28)
project(hashTable)

set(CMAKE_CXX_STANDARD 17)

add_executable(hashTable main.cpp
        HashTable.cpp
        HashTable.h)
