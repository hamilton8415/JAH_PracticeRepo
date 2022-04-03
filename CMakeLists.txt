cmake_minimum_required(VERSION 3.16.3)

project(
  PracticeRepo 
  LANGUAGES CXX)

#add_compile_options()
# Only do these if this is the main project, and not if it is included through add_subdirectory
if(CMAKE_PROJECT_NAME STREQUAL PROJECT_NAME)
  set(CMAKE_CXX_STANDARD 11)
  set(CMAKE_CXX_STANDARD_REQUIRED True)
endif()

add_subdirectory(src)

#add_subdirectory(docs)

#add_subdirectory(tests/gtest)


