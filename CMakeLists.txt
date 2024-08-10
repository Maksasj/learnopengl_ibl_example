cmake_minimum_required(VERSION 3.21)
project(LearnOpenGL_IBL_Example)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unknown-pragmas")

add_subdirectory(3dparty)
add_subdirectory(src)