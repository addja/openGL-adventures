cmake_minimum_required(VERSION 3.8)
  
project("openGL-adventures")
set(CMAKE_CXX_STANDARD 17)

add_subdirectory(src)

# external libraries
add_subdirectory(glad)
add_subdirectory(glfw)
