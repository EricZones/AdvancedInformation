cmake_minimum_required(VERSION 3.30)
project(AdvancedInformation C)

include_directories(${PROJECT_SOURCE_DIR}/include)

set(CMAKE_C_STANDARD 23)
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -O2 -fPIC")

add_library(AdvancedInformation SHARED src/plugin.c)

set_target_properties(AdvancedInformation PROPERTIES PREFIX "")