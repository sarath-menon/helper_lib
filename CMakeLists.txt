cmake_minimum_required(VERSION 3.20.0)
set(CMAKE_CXX_STANDARD 17)
project(helper_lib VERSION 0.1.0)

include(CTest)
enable_testing()


set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)

add_subdirectory(helper)
add_subdirectory(tests)
