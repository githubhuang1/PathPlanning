cmake_minimum_required(VERSION 3.16.0)

project(search_based_planning)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

include_directories(
    include
)

target_link_libraries(search_based_planning_lib src/*.cpp)