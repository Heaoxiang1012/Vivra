cmake_minimum_required(VERSION 3.15)
project(vivra)

set(CMAKE_STANDARD 17)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include_directories(${PROJECT_SOURCE_DIR}/include)

add_subdirectory(app)
add_subdirectory(src)

include(clang-format.cmake)