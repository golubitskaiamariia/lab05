cmake_minimum_required(VERSION 3.5)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(project)

add_subdirectory(banking)
add_subdirectory(third-party/gtest)
add_subdirectory(tests)

