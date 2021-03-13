cmake_minimum_required(VERSION 3.10)

project(
    HelloWorld
    VERSION 0.1
    DESCRIPTION "Hello World for cmake C++ Project"
)

set(CMAKE_CXX_STANDARD 17)
set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)

add_executable(HelloWorld main.cpp)