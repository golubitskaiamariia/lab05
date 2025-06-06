cmake_minimum_required(VERSION 3.5)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_compile_options(--coverage)
add_link_options(--coverage)

project(project)

add_subdirectory(banking)
add_subdirectory(third-party/gtest)
add_subdirectory(tests)

