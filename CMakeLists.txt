cmake_minimum_required(VERSION 3.10)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(Projects)

add_subdirectory(formatter_ex_lib)
add_subdirectory(solver_lib)
add_subdirectory(formatter_lib)

add_subdirectory(hello_world_application)
add_subdirectory(solver_application)

