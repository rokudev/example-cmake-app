
cmake_minimum_required(VERSION 3.1...3.24)
project(
  NeilArmstrong
  VERSION 1.0
  LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_subdirectory(src)

include(GNUInstallDirs)
