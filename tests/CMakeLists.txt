cmake_minimum_required(VERSION 3.5)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(test)

enable_testing()

add_executable(test test.cpp)
target_link_libraries(test PRIVATE banking gtest gmock)

add_test(tests_dz5 test)

